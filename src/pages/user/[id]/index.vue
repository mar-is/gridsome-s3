<template>
	<Layout>
		{{ JSON.stringify(route) }}
	</Layout>
</template>

<script>
export default {
	name: "UserDetail",

	computed: {
		route() {
      const {params} = this.$route;

			return params
		}
	}
};
</script>

<style></style>
