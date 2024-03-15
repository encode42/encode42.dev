<script>
	import "@catppuccin/palette/css/catppuccin.css";
	import "@fontsource-variable/jetbrains-mono";
</script>

<div>
	<h1>This website is <em>Under Construction!</em></h1>
	<p>Meanwhile, please visit the following links:</p>
	<ul>
		<li><a href="https://github.com/encode42">github</a></li>
		<li><a href="https://erora.live">music</a></li>
		<li><a href="https://youtube.com/@encode42">youtube</a></li>
		<li><a href="https://encode42.dev/discord">discord</a></li>
		<li><a href="mailto:me@encode42.dev">e-mail</a></li>
	</ul>
</div>

<style>
	div {
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	h1 {
		font-family: "Jetbrains Mono", monospace;
		font-size: 3rem;
		color: var(--ctp-macchiato-mauve);
	}

	p, li {
		font-size: 1.25rem;
		color: var(--ctp-macchiato-text);
	}

	li {
		padding-left: 1rem;
		line-height: 2rem;
		font-family: "Jetbrains Mono", monospace;
	}

	a, em {
		color: var(--ctp-macchiato-green);
	}

	a:hover {
		background: var(--ctp-macchiato-green);
		color: var(--ctp-macchiato-base);
		outline: 0.5rem solid var(--ctp-macchiato-green);
		border-radius: 0.5rem;
	}
</style>
