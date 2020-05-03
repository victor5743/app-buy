<template>
	<div class="px-8 py-4 border-b-2 border-gray-500">
		<div class="sm:flex justify-between">
			<!-- Logo and menu button -->
			<div class="flex items-center justify-between sm:mb-0 mb-4">
				<!-- Logo -->
				<div class="flex items-center">
					<a href="#"><img class="h-12 w-12" src="../assets/logo.png" alt="Logo app"/></a>
					<a href="#" class="text-xl font-semibold text-gray-800">Vue-App</a>
				</div>
				<!-- Menu button -->
				<div class="sm:hidden">
					<button
						@click="isOpen = !isOpen"
						class="text-gray-600 hover:text-gray-700 focus:text-gray-700 focus:outline-none"
					>
						<svg
							class="fill-current h-6 w-6"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								v-if="!isOpen"
								d="M10 8.586L2.929 1.515 1.515 2.929 8.586 10l-7.071 7.071 1.414 1.414L10 11.414l7.071 7.071 1.414-1.414L11.414 10l7.071-7.071-1.414-1.414L10 8.586z"
							/>
							<path v-if="isOpen" d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
						</svg>
					</button>
				</div>
			</div>

			<!-- Links -->
			<div v-if="!isOpen" class="sm:flex items-center">
				<a
					class="block hover:text-white hover:bg-gray-800 px-2 py-1 rounded-md text-right"
					href="#"
					>Download</a
				>
				<a
					class="block hover:text-white hover:bg-gray-800 px-2 py-1 rounded-md sm:ml-8 ml-0 text-right"
					href="#"
					>Learn More</a
				>
				<a
					class="block hover:text-white hover:bg-gray-800 px-2 py-1 rounded-md sm:ml-8 ml-0 text-right"
					href="#"
					>Pricing</a
				>
				<a
					class="block hover:text-white hover:bg-gray-800 px-2 py-1 rounded-md sm:ml-8 ml-0 sm:mb-0 mb-6 text-right"
					href="#"
					>Help</a
				>
				<a
					class="block sm:ml-8 ml-0 btn-gray btn-gray:hover cursor-pointer text-center sm:text-left"
					>Account</a
				>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {
			isOpen: false,
		};
	},
};
</script>
