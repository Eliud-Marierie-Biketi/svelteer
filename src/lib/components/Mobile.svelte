<script>
	import Hero from './Hero.svelte';
</script>

<div id="contact" class="p-4 xl:p-10 bg-base-300 my-10 rounded-lg">
	<div class="max-w-lg mx-auto pb-10">
		<div class="text-3xl font-bold text-center my-5">Contact Us</div>
		<div class="text-lg text-center my-5">
			Get intouch with us.
		</div>
		<div class="flex justify-center gap-4 my-5">
			<a href="https://www.tiktok.com" target="_blank" class="text-2xl text-gray-600 hover:text-gray-800">
				<i class="fab fa-tiktok"></i>
			</a>
			<a href="https://www.youtube.com" target="_blank" class="text-2xl text-gray-600 hover:text-gray-800">
				<i class="fab fa-youtube"></i>
			</a>
			<a href="https://www.facebook.com" target="_blank" class="text-2xl text-gray-600 hover:text-gray-800">
				<i class="fab fa-facebook"></i>
			</a>
			<a href="https://www.instagram.com" target="_blank" class="text-2xl text-gray-600 hover:text-gray-800">
				<i class="fab fa-instagram"></i>
			</a>
			<a href="https://twitter.com" target="_blank" class="text-2xl text-gray-600 hover:text-gray-800">
				<i class="fab fa-twitter"></i>
			</a>
		</div>
	</div>
	

	<div class="flex justify-center">
		<div class="mockup-phone shadow-xl">
			<div class="camera" />
			<div class="display">
				<div class="artboard artboard-demo phone-1">
					<Hero />
				</div>
			</div>
		</div>
	</div>
</div>
