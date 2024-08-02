<script lang="ts">
    import { enhance, type SubmitFunction } from '$app/forms';
    import { page } from '$app/stores';
    import '$lib/app.css';
    import { themes } from '$lib/utils/themes';

    const submitUpdateTheme: SubmitFunction = ({ action }) => {
        const theme = action.searchParams.get('theme');

        if (theme) {
            document.documentElement.setAttribute('data-theme', theme);
        }
    };
</script>

<div class="bg-base-100 sticky top-0 shadow-lg z-40">
    <div class="flex flex-wrap items-center justify-between p-2 w-full max-w-4xl mx-auto">
        <div class="flex items-center">
            <a href="/" class="font-bold text-primary text-xl font-serif">POET-ESS-ENTIAL</a>
        </div>

        <div class="flex flex-wrap items-center space-x-4 mt-2">
            <a href="#home" class="text-lg font-medium hover:text-primary border-b-2 border-black rounded-t-lg px-2 py-1">Home</a>
            <a href="#about" class="text-lg font-medium hover:text-primary border-b-2 border-black rounded-t-lg px-2 py-1">About Us</a>
            <a href="#contact" class="text-lg font-medium hover:text-primary border-b-2 border-black rounded-t-lg px-2 py-1">Contact Us</a>

            <div class="dropdown dropdown-hover dropdown-end">
                <!-- svelte-ignore a11y-label-has-associated-control -->
                <label class="btn">Theme</label>
                <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
                <ul tabindex="0" class="dropdown-content menu p-2 shadow bg-base-100 h-96 overflow-scroll">
                    <form method="POST" use:enhance={submitUpdateTheme}>
                        {#each themes as theme}
                            <li>
                                <button formaction="/?/setTheme&theme={theme}&redirectTo={$page.url.pathname}"
                                    >{theme}</button
                                >
                            </li>
                        {/each}
                    </form>
                </ul>
            </div>
        </div>
    </div>
</div>
