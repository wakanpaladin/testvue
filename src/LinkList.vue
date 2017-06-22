<template>

<ul>
  <li v-for="l in links" target>
  	<a :href=l.link target="_blank">{{l.name}}</a>
  </li>
</ul>
</template>

<script type="text/javascript">
export default {
	data(){
		return {
			links:[
				{link:'https://vuejs.org',name:'vuejs'},
				{link:'https://vuejs.org',name:'vuejs2'},
			]
		}
	}
}
</script>
