<template>
	<div>
		<!-- Navbar component -->
		<Navbar />

		<!-- Checkout -->
		<div class="block sm:flex mt-16 mx-auto max-w-2xl rounded-lg shadow-lg px-8 py-8">
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
						<div class="block">
							<div class="flex">
								<div class="w-1/2 mb-2 mr-1">
									<label class="block text-sm mb-2 text-gray-800" for="first_name"
										>First Name</label
									>
									<input
										id="first_name"
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
										id="last_name"
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
									id="email"
									class="w-full input-gray input-gray:focus"
									type="email"
									placeholder="email@example.com"
								/>
							</div>
						</div>
						<!-- Second section -->
						<div class="mt-8 border-t border-gray-400">
							<div class="flex items-center mb-4 mt-8">
								<div class="border-2 border-primary rounded-full py-2 px-4 mr-2">
									2
								</div>
								<h2 class="text-">Your Payment Information</h2>
							</div>
							<div class="w-full">
								<label class="block text-sm mb-2 text-gray-800" for="email"
									>Credit Card</label
								>
								<input
									id="payment"
									class="w-full input-gray input-gray:focus"
									type="text"
									placeholder="Card Number"
								/>
							</div>
							<!-- Button -->
							<div class="mt-4">
								<button
									class="bg-secondary w-full px-4 py-2 rounded-md text-white mb-4 text-lg hover:bg-tertiary"
									type="submit"
								>
									Buy Vue App
								</button>
							</div>
							<!-- Help section -->
							<div class="flex items-center text-secondary">
								<svg
									class="h-5 w-5 fill-current"
									xmlns="http://www.w3.org/2000/svg"
									viewBox="0 0 20 20"
								>
									<path
										d="M10 20a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm2-13c0 .28-.21.8-.42 1L10 9.58c-.57.58-1 1.6-1 2.42v1h2v-1c0-.29.21-.8.42-1L13 9.42c.57-.58 1-1.6 1-2.42a4 4 0 1 0-8 0h2a2 2 0 1 1 4 0zm-3 8v2h2v-2H9z"
									/>
								</svg>
								<div>
									<span class="font-bold text-gray-800 font-semibold ml-2 text-xs">
										Need any help?
									</span>
									<span class="text-xs text-gray-800">
										Don't hesitate to
										<a class="underline text-gray-700 text-xs" href="#"
											>contact support</a
										>
									</span>
								</div>
							</div>
						</div>
						<!-- End Second Section -->
					</div>
					<!-- End Panel -->
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
