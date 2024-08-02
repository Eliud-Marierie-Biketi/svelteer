<script>

	import image1 from '$lib/images/pexels-12th-5-blog-803104198-19194587.jpg'
	import image2 from '$lib/images/pexels-willianjusten-18631993.jpg';

</script>
<div id="about" class="bg-base-300 p-4 xl:p-10 rounded-lg">
    <div class="text-center mb-10">
        <h1 class="text-4xl font-bold mb-4">Celebrating African Poets</h1>
        <p class="text-lg">
            Welcome to Poet-ential, where we honor the rich and diverse literary tradition of African poetry. Our mission is to bring the voices of renowned poets across Africa to a global audience. Explore this section to discover timeless works and gain insights into the poetic expressions that shape African culture and heritage.
        </p>
    </div>

    <div class="flex flex-col lg:flex-row xl:gap-10">
        <div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg mb-5 lg:mb-0">
            <div class="p-4 xl:p-10">
                <img
                    alt="African Poet 1"
                    src={image1}
                    class="h-64 w-full object-cover rounded-lg shadow-lg mb-4"
                />
                <h2 class="text-2xl font-semibold mb-2">Poet 1</h2>
                <p class="text-lg">
                    Explore the profound works of Poet 1, whose evocative poems capture the essence of African landscapes and cultural narratives. 
                </p>
            </div>
        </div>

        <div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
            <div class="p-4 xl:p-10">
                <img
                    alt="African Poet 2"
                    src={image2}
                    class="h-64 w-full object-cover rounded-lg shadow-lg mb-4"
                />
                <h2 class="text-2xl font-semibold mb-2">Poet 2</h2>
                <p class="text-lg">
                    Discover the powerful poetry of Poet 2, whose works reflect the rhythm and beauty of African oral traditions and contemporary experiences.
                </p>
            </div>
        </div>
    </div>
</div>
