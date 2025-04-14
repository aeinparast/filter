<script lang="ts">
	import Header from './Header.svelte';
	import '../app.css';

	let { children } = $props();

	function openPopup() {
		window.open(
			'https://logo.samandehi.ir/Verify.aspx?id=375855&p=xlaojyoedshwmcsidshwdshw',
			'Popup',
			'toolbar=no,scrollbars=no,location=no,statusbar=no,menubar=no,resizable=0,width=450,height=630,top=30'
		);
	}
</script>

<div class="app">
	<Header />

	<main>
		{@render children()}
	</main>

	<footer>
		<button on:click={openPopup} class="logo-button">
			<img
				referrerpolicy="origin"
				alt="logo-samandehi"
				src="https://logo.samandehi.ir/logo.aspx?id=375855&p=qftiyndtujynaqgwujynujyn"
			/>
		</button>
		<a
			href="https://farsi.khamenei.ir/message-content?id=59757"
			target="_blank"
			rel="noopener noreferrer">سال سرمایه‌گذاری برای تولید</a
		>
	</footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}

	.logo-button {
		background: none;
		border: none;
		padding: 0;
		cursor: pointer;
	}
</style>
