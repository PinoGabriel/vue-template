<script>
import AppComponent from './components/AppComponent.vue'
import { store } from './store.js'
import axios from 'axios'

export default {
	components: {
		AppComponent,
	},
	data() {
		return {
			store,
		}
	},
	methods: {

	}
}
</script>

<template>
	<header>
	</header>
	<main>
		<AppComponent />
	</main>
	<footer></footer>
</template>

<style lang="scss">
@use './styles/general.scss';
</style>

<style scoped lang="scss">
@use './styles/partials/variables' as *;
</style>
