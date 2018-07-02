<template>
	<div class="home">
		<Header></Header>
		<Swiper></Swiper>
		<home-icons></home-icons>
	</div>
</template>

<script>
	import Header from './header'
	import Swiper from './Swiper'
	import HomeIcons from './components/Icons'

	export default {
		data(){
			return {
				msg:'hello world'
			}
		},
		components:{
			Header,
			Swiper,
			HomeIcons
		}
	}
</script>

<style lang="stylus" scoped>
	 
</style>