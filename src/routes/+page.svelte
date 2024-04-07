<script>
	import '../app.css';
</script>

<svelte:head>
	<title>Hello Tippio ⚡</title>
</svelte:head>

<div class="flex flex-col min-h-screen bg-black text-gray-50 bg-[url('/bg.webp')] bg-cover">
	<main class="grow max-w-screen-xl mx-auto px-6 w-full flex flex-col items-center">
		<h1 class="center my-16 md:mt-24 md:mb-12">
			<img src="/tippio.png" alt="Tippio" class="w-[310px] h-[80px]" />
		</h1>
		<h2 class="text-4xl md:text-6xl center font-bold font-open-sans text-gray-200 text-center">
			Revolutionizing Tipping
		</h2>
		<h3 class="text-[18px] center mt-5 mb-6 max-w-lg text-center text-[#D3D3D3] font-open-sans">
			Tippio, the innovative web application that empowers seamless tipping within the Solana
			ecosystem
		</h3>
		<a
			href="/Tippio.pdf"
			target="_blank"
			class="text-[14px] bg-[#4800FF] hover:bg-[#4840FF] text-gray-200 font-poppins font-bold py-4 px-10 rounded"
			>Get Started</a
		>
		<img src="/browser.webp" alt="Browser" class="mt-16 mb-16 md:mt-32 md:mb-24 mx-auto block" />
	</main>
	<footer
		class="text-center max-w-screen-xl mx-auto px-6 w-full my-4 font-open-sans text-[#D3D3D3] text-base md:text-lg"
	>
		Copyright © 2024 Tippio. All rights reserved.
	</footer>
</div>
