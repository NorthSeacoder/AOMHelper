<template>
	
		<uni-grid :options=options
		column-num="2"
		show-border="false"
		type="oblong"
		@click="onClick">
		</uni-grid>
	
</template>

<script>
	import uniGrid from "@/components/uni-grid/uni-grid.vue"
	import {gridOptions} from "./constant/options.js"
	export default {
		components: {uniGrid},
		data() {
			return {
				options:gridOptions
			}
		},
		methods: {
			onClick(res){
				console.log(res)
			}
		}
	}
</script>

<style>

</style>
