<script lang="ts">
	import rayanImage from '$lib/images/rayan.webp';
</script>

<svelte:head>
	<title>درباره من | خدمات برنامه نویسی آئین‌پرست</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column" dir="rtl">
	<img
		src={rayanImage}
		alt="آئین‌پرست برنامه نویس"
		loading="lazy"
		class="w-80 rounded-full mx-auto hover:scale-95 transition-transform"
	/>

	<h1>درباره من</h1>

	<p>
		من محمدامین آئین‌پرست دانش آموخته کارشناسی رشته مهندسی حرفه‌ای کامپیوتر با گرایش نرم‌افزار از <a
			href="https://p-rasht.nus.ac.ir/"
			target="_blank"
			rel="noopener noreferrer">دانشگاه ملی مهارت شهید چمران رشت</a
		> هستم.
	</p>

	<p>خدمات من:</p>

	<ul>
		<li>طراحی وبسایت و وب‌اپلیکیشن با استفاده از Laravel، SvelteKit و React.</li>
		<li>آموزش برنامه نویسی به زبان‌های JavaScript/TypeScript، php و پایتون.</li>
		<li>اجرا و نگهداری برنامه‌های از پیش آماده یا انتقال به فضای ابری.</li>
	</ul>

	<p>
		چنانچه نیاز به مشاوره و کسب اطلاعات بیشتر دارید میتوانید با شماره
		<a href="tel:+989376309329">09376309329</a>
		یا ایمیل من به آدرس: <a href="mailto:rayanaeinparast@gmail.com">rayanaeinparast@gmail.com</a>
		در ارتباط باشید.
	</p>
</div>
