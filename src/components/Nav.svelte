<script>
  export let segment;
</script>

<style>
  nav {
    font-weight: 300;
    padding: 0 10em;
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
		background-color: #f8f8f8;
		align-items: center;
		height: 100px;
		font-family: serif;
  }

	nav .links {
		display: flex;
		flex-flow: row wrap;
		justify-content: space-between;
	}
  a {
    text-decoration: none;
    padding: 1em 0.5em;
    display: block;
		margin: 0 50px;
		text-transform: uppercase;
		font-size: 16px;
		cursor: pointer;
  }
</style>

<nav>
  <div class="icon">icon</div>
  <div class="links">
		<a>Work</a>
		<a>About</a>
		<a>Social</a>
	</div>
  <div class="contact">
		<a>Contact</a>
	</div>
</nav>
