<template>
	<div>
		<!-- Navbar component -->
		<Navbar />

		<!-- Checkout -->
		<Checkout />
	</div>
</template>

<script>
import Navbar from './Navbar.vue';
import Checkout from './Checkout.vue';

export default {
	components: {
		Navbar,
		Checkout,
	},
};
</script>
