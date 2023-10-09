<script lang="ts">
</script>

<div class="mt-[55px] flex w-full flex-row">
	<section class="flex w-full flex-col justify-end">
		<h1 class="pl-20 text-6xl font-bold text-[#252525]">
			Hi! I'm <span class="text-gradient">Hengers</span> a
			<br />
			Full Stack <span class="text-gradient">Developer</span>
		</h1>
		<section class="flex w-full flex-row justify-evenly pt-6">
			<a href="https://github.com/hengers">
				<button class="btn btn-primary">GitHub </button>
			</a>
			<a href="https://www.linkedin.com/in/hengers-dev/">
				<button class="btn btn-primary">LinkedIn</button>
			</a>
			<a href="https://twitter.com/hengers_dev">
				<button class="btn btn-primary">Twitter</button>
			</a>
			<a href="https://www.instagram.com/hengers_dev/">
				<button class="btn btn-primary">Instagram</button>
			</a>
		</section>
	</section>
	<section class="relative flex w-full flex-row justify-center">
		<div class="background_image absolute -z-10 h-[533px] w-[450px] bg-black opacity-50"></div>
		<img src="../assets/image-profile.png" alt="" width="450" />
	</section>
</div>

<style>
	.text-gradient {
		background-image: var(--accent-gradient);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-size: 400%;
		background-position: 0%;
	}
	.background_image {
		border-radius: 100px 100px 50px 50px;
	}
</style>
