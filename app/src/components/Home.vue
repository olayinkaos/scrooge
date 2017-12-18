<template>
	<div class="home">
		<h1 class="title">
			Welcome, <br>
			I'll be your Scrooge today 👿
		</h1>
		<div class="columns">
			<div class="column">
				<form action="">
					<div class="field">
						<div class="control">
							<input class="input" type="number" placeholder="Enter expenditure">
						</div>
					</div>
					<div class="field">
						<div class="control">
							<textarea class="textarea" name="" id="" cols="30" rows="3" placeholder="Description (Optional)"></textarea>
						</div>
					</div>
					<div class="field is-grouped">
						<button class="button is-link is-fullwidth">Submit</button>
					</div>
				</form>
			</div>
			<div class="column">

			</div>
			<div class="column">

			</div>
		</div>

	</div>
</template>

<script>
export default {
	name: 'Home',
	data () {
		return {
			like: 'dat'
		}
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
