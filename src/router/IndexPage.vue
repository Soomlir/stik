<script>
import ProductComponent from '@/components/blocks/ProductComponent.vue';

export default {
	components: {
		ProductComponent,
	},
};
</script>

<template>
	<main class="main">
		<ProductComponent />
	</main>
</template>

<style lang="scss">
.main {
	@media (min-width: 1440px) {
		max-width: 1440px;
		margin-right: auto;
		margin-left: auto;
	}
}
</style>
