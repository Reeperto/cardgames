<nav class="navbar">
	<a class="navbar-link" href="/">Home</a>
	<a class="navbar-link" href="/games/war">War</a>
</nav>

<slot></slot>

<style lang="scss">

  .navbar {
		max-width: 40vw;

		display: flex;
		justify-content: space-around;

		margin: auto;

		border: 1pt solid black;

		&-link {
			text-decoration: none;
			font-size: 2rem;
		}
	}

</style>
