<template>
	<div class="home">
		<Header></Header>
		<h1>hello world</h1>
	</div>
</template>

<script>
	import Header from './header'

	export default {
		data(){
			return {
				msg:'hello world'
			}
		},
		components:{
			Header
		}
	}
</script>

<style lang="stylus" scoped>
	
</style>