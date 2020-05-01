<template>
    <div class="row">
        <div class="col-xs-12">
            <header>
                <h1>Server Status {{title}}</h1>
            </header>
        </div>
    </div>
</template>

<script>
export default {
	props: {
	  title: { 
        type: Object,
        required: true
    }
	}
};
</script>

<style>

</style>
