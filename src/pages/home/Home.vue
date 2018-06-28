<template>
	<div class="home">
		<Header></Header>
		<Swiper></Swiper>
		<h1>hello world</h1>
	</div>
</template>

<script>
	import Header from './header'
	import Swiper from './Swiper'

	export default {
		data(){
			return {
				msg:'hello world'
			}
		},
		components:{
			Header,
			Swiper
		}
	}
</script>

<style lang="stylus" scoped>
	
</style>