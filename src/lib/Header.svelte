<script>
	import TvIcon from './TvIcon.svelte';
</script>

<div
	class="max-w-4xl mx-auto w-full flex md:flex-row flex-col items-center md:justify-between py-8 mb-12 border-b border-white/20"
>
	<button on:click class="flex items-center mb-4 md:mb-0 text-white/70">
		<TvIcon />
		<div class="text-2xl md:text-xl font-bold ml-2">Self Care & Chill</div>
	</button>
	<a
		class="bg-white/20 hover:bg-white/50 shadow text-white hover:text-pink-600 font-medium rounded p-2 text-sm flex items-center"
		href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FB8N4S8N%2FN-C&env=OPENAI_API_KEY,OMDB_API_KEY&envDescription=Go%20to%20Open%20AI.%20Sign%20up.%20Get%20your%20API%20key.%20%20Enter%20the%20API%20key%20in%20ENV%20Variables%20and%20LFG!!!%20%20%20After%20that%20head%20to%20https%3A%2F%2Fwww.omdbapi.com%2F%20sign%20up%20and%20follow%20the%20instructions%20to%20get%20your%20API%20key.%20Enter%20it%20and%20LFG!!!&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys"
	>
		<span class="button_prefix__e8xDo"
			><svg height="16" viewBox="0 0 113 100" width="16" xmlns="http://www.w3.org/2000/svg"
				><defs
					><linearGradient id="a" x1="196.57%" x2="50%" y1="228.82%" y2="50%"
						><stop offset="0%" /><stop offset="100%" stop-color="currentColor" /></linearGradient
					></defs
				><path
					d="M350.5 150L407 250H294z"
					fill="url(#a)"
					fill-rule="evenodd"
					transform="translate(-294 -150)"
				/></svg
			></span
		>
		<span class="ml-2">Deploy</span>
	</a>
</div>
