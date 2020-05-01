
<template>
	<div>
		<p>This status is {{status}}</p>
		<button @click="changeevent">Change Status</button>
	</div>
</template>
<script>
	export default {
      data: function() {
      	return{
      	status: "Critical"
      	}
       },
       methods:{
       	changeevent(){
       		this.status = "Normal"
       	}
       }
	};
</script>