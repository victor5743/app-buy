<template>
	<div>
		<!-- Navbar component -->
		<Navbar />

		<!-- Checkout -->
		<div class="flex mt-16 mx-auto max-w-2xl rounded-lg shadow-lg px-8 py-8">
			<div class="w-2/3 pr-8">
				<form action="">
					<h1 class="border-b pb-8 text-xl text-gray-800">Checkout</h1>
					<div class="pt-8 border-t border-gray-400">
						<!-- First section -->
						<div class="flex items-center mb-4">
							<div class="border-2 border-primary rounded-full py-2 px-4 mr-2">
								1
							</div>
							<h2 class="text-">Your Basic Information</h2>
						</div>

						<!-- Second section -->
						<div class="block">
							<div class="flex">
								<div class="w-1/2 mb-2 mr-1">
									<label class="block text-sm mb-2 text-gray-800" for="first_name"
										>First Name</label
									>
									<input
										class="w-full input-gray input-gray:focus"
										type="text"
										placeholder="Jone"
									/>
								</div>
								<div class="w-1/2 mb-2 ml-1">
									<label class="block text-sm mb-2 text-gray-800" for="last_name"
										>Last Name</label
									>
									<input
										class="w-full input-gray"
										input-gray:focus
										type="text"
										placeholder="Smith"
									/>
								</div>
							</div>
							<div class="w-full">
								<label class="block text-sm mb-2 text-gray-800" for="email">Email</label>
								<input
									class="w-full input-gray input-gray:focus"
									type="text"
									placeholder="email@example.com"
								/>
							</div>
						</div>
					</div>
				</form>
			</div>
			<div class="w-1/3 bg-primary">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima ipsa mollitia
				ducimus? Id voluptatum officia, harum ducimus quas alias labore quisquam
				accusantium quod aliquam ea, eius optio minima aspernatur explicabo.
			</div>
		</div>
	</div>
</template>

<script>
import Navbar from './Navbar.vue';

export default {
	components: {
		Navbar,
	},
};
</script>
