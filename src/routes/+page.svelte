<script lang="ts">
	import whitboard from '$lib/images/whiteboard.svg';
	import laravel from '$lib/images/laravel.svg';
	import talk from '$lib/images/talk.svg';
</script>

<svelte:head>
	<title>خانه | خدمات برنامه نویسی آئین‌پرست</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section dir="rtl">
	<h1>خدمات برنامه‌نویسی و آموزشی آئین‌پرست</h1>

	<h2 class="!text-3xl">خدمات من:</h2>
	<div class="flex flex-col gap-4 mt-8">
		<div
			class="border p-5 flex flex-col items-center gap-2 rounded-2xl hover:scale-95 transition-all"
		>
			<img
				src={whitboard}
				alt="آئین‌پرست برنامه نویس"
				loading="lazy"
				class="w-72
				 mx-auto hover:scale-95 transition-transform"
			/>
			<h3 class="text-2xl">تدریس</h3>
			<p class="text-center">
				آموزش مدیریت سایت با وردپرس یا آموزش توسعه وب‌اپلیکیشن با SvelteKit، React، Laravel و
				JavaScript/TypeScript
			</p>
		</div>
		<div
			class="border p-5 flex flex-col items-center gap-2 rounded-2xl hover:scale-95 transition-all"
		>
			<img
				src={laravel}
				alt="آئین‌پرست برنامه نویس"
				loading="lazy"
				class="w-72
		 mx-auto hover:scale-95 transition-transform"
			/>
			<h3 class="text-2xl">توسعه وبسایت</h3>
			<p class="text-center">
				اگر درنظر دارید که یک وبسایت یا یک وب‌اپلیکیشن برای خود یا کسب‌وکار خود داشته باشید، کافیست
				با من در تماس باشید.
			</p>
		</div>
		<div
			class="border p-5 flex flex-col items-center gap-2 rounded-2xl hover:scale-95 transition-all"
		>
			<img
				src={talk}
				alt="آئین‌پرست برنامه نویس"
				loading="lazy"
				class="w-72
		 mx-auto hover:scale-95 transition-transform"
			/>
			<h3 class="text-2xl">مشاوره</h3>
			<p class="text-center">
				اگر برای کسب و کار شما در بخش IT مشکلی پیش آمده و سعی در حل آن دارید، میتوانید با من در
				ارتباط باشید. ضمن آنکه امکان بررسی و بروزآوری کدبیس های قدیمی نیز وجود دارد.
			</p>
		</div>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
