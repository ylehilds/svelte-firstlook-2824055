<script>
	export let name;
</script>

<style lang="scss">
    $primary: purple;

    @import "../node_modules/bootstrap/scss/bootstrap.scss";

	h1 {
		color: $primary;
	}
</style>

<div class="container">
    <h1>Hello {name}!</h1>
    <p class="text-primary">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur varius tortor nec mauris lobortis tristique. Quisque metus risus, pretium nec magna non, mattis maximus purus. Aenean convallis odio vitae varius lacinia. Sed a ligula mollis, semper enim nec, pellentesque risus. Donec a finibus justo. Vivamus pellentesque eget leo nec volutpat. In in euismod dolor. Vestibulum sit amet erat sed ipsum rhoncus pretium.</p>
</div>
