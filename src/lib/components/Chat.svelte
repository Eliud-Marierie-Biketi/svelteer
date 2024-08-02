<script>
	import image1 from '$lib/images/pexels-12th-5-blog-803104198-19194587.jpg'
	import image2 from '$lib/images/pexels-willianjusten-18631993.jpg';
</script>

<div id="about" class="bg-base-300 p-4 xl:p-10 rounded-lg">
    <div class="max-w-lg mx-auto pb-10">
        <div class="text-3xl font-bold text-center my-5">About Us </div>
        <div class="text-lg text-center my-5">
            We are a growing movement, showcasing the art of poetry all the way from African traditory to modern.
			We also offer a wide range of creative expression.
			We are a community of poetry enthusiasts, artists, and writers.
			We like to share our love of poetry with the world.
        </div>
    </div>

    <div class="flex flex-col lg:flex-row justify-center gap-5 xl:gap-10">
        <div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
            <div class="p-4 xl:p-10">
                <!-- MSG 1 -->
                <div class="chat chat-start mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image1} alt="Close-up of cotton plants in a field" />
                        </div>
                    </div>
                    <div class="chat-header">
                        Eliud Marierie
                        <time class="text-xs opacity-50">12:45</time>
                    </div>
                    <div class="chat-bubble">Hello world</div>
                    <div class="chat-footer opacity-50">Delivered</div>
                </div>

                <!-- MSG 2 -->
                <div class="chat chat-start mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image2} alt="Close-up of cotton plants in a field" />
                        </div>
                    </div>
                    <div class="chat-header">
                        Marge Simpson
                        <time class="text-xs opacity-50">12:48</time>
                    </div>
                    <div class="chat-bubble">You were the Chosen One!</div>
                    <div class="chat-footer opacity-50">Delivered</div>
                </div>

                <!-- MSG 3 -->
                <div class="chat chat-end mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image1} alt="Close-up of cotton plants in a field" />
                        </div>
                    </div>
                    <div class="chat-header">
                        Elon Musk
                        <time class="text-xs opacity-50">12:51</time>
                    </div>
                    <div class="chat-bubble bg-primary">Thanks 🙂👍</div>
                    <div class="chat-footer opacity-50">Seen at 12:46</div>
                </div>
            </div>
        </div>
        <div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
            <div class="p-4 xl:p-10">
                <!-- MSG 1 -->
                <div class="chat chat-start mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image1} alt="Close-up of cotton plants in a field" />
                        </div>
                    </div>
                    <div class="chat-header">
                        Ada Lovelace
                        <time class="text-xs opacity-50">12:45</time>
                    </div>
                    <div class="chat-bubble">Hello world</div>
                    <div class="chat-footer opacity-50">Delivered</div>
                </div>

                <!-- MSG 2 -->
                <div class="chat chat-end mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image2} alt="Close-up of cotton plants in a field" />
                        </div>
                    </div>
                    <div class="chat-header">
                        Anakin
                        <time class="text-xs opacity-50">12:46</time>
                    </div>
                    <div class="chat-bubble bg-primary">I hate you!</div>
                    <div class="chat-footer opacity-50">Seen at 12:46</div>
                </div>

                <!-- MSG 3 -->
                <div class="chat chat-end mb-4">
                    <div class="chat-image avatar">
                        <div class="w-10 rounded-full">
                            <img src={image2} alt="Close-up of cotton plants in " />
                        </div>
                    </div>
                    <div class="chat-header">
                        Anakin
                        <time class="text-xs opacity-50">12:46</time>
                    </div>
                    <div class="chat-bubble bg-primary">I hate you!</div>
                    <div class="chat-footer opacity-50">Seen at 12:46</div>
                </div>
            </div>
        </div>
    </div>
</div>
