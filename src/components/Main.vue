<template>
	<div>
		<!-- Navbar component -->
		<Navbar />

		<!-- Checkout -->
		<div class="block p-8 sm:p-0 sm:flex my-16 mx-auto max-w-3xl rounded-lg shadow-lg">
			<!-- Left panel -->
			<div class="w-full sm:w-2/3 p-8">
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
							<div class="block sm:flex">
								<div class="w-full sm:w-1/2 mb-2 sm:mr-1">
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
								<div class="w-full sm:w-1/2 mb-2 sm:ml-1">
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
				</form>
			</div>
			<!-- End Panel -->

			<!-- Right panel -->
			<div class="block w-full sm:w-1/3 bg-primary p-8 text-white">
				<h2 class="font-semibold text-xl mb-4 text-white">Freelancer</h2>
				<span class="text-3xl">$</span>
				<span class="text-5xl font-light">99</span>
				<span class="text-lg font-light">/ year</span>
				<div class="w-3/4 italic leading-normal mb-8">
					Automatically renews after 1 year
				</div>
				<div>
					<ul>
						<li class="mb-4 flex items-center">
							<svg
								class="h-4 w-4 fill-current"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM6.7 9.29L9 11.6l4.3-4.3 1.4 1.42L9 14.4l-3.7-3.7 1.4-1.42z"
								/>
							</svg>
							<span class="ml-2">Use on 5 client sites</span>
						</li>
						<li class="mb-4 flex items-center">
							<svg
								class="h-4 w-4 fill-current"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM6.7 9.29L9 11.6l4.3-4.3 1.4 1.42L9 14.4l-3.7-3.7 1.4-1.42z"
								/>
							</svg>
							<span class="ml-2">Private Repositories</span>
						</li>
						<li class="mb-8 flex items-center">
							<svg
								class="h-4 w-4 fill-current"
								xmlns="http://www.w3.org/2000/svg"
								viewBox="0 0 20 20"
							>
								<path
									d="M2.93 17.07A10 10 0 1 1 17.07 2.93 10 10 0 0 1 2.93 17.07zm12.73-1.41A8 8 0 1 0 4.34 4.34a8 8 0 0 0 11.32 11.32zM6.7 9.29L9 11.6l4.3-4.3 1.4 1.42L9 14.4l-3.7-3.7 1.4-1.42z"
								/>
							</svg>
							<span class="ml-2">Email Support</span>
						</li>
					</ul>
					<!-- End list items -->
					<div class="border-t-2 border-white py-8">
						<span>
							FTP is horrible to deal with. Vue App solves that issue, and the customer
							support is awesome!
						</span>
						<img
							class="w-24 h-24 object-cover rounded-full mx-auto mt-8"
							src="../assets/24998.jpg"
							alt="Avatar"
							srcset=""
						/>
					</div>
				</div>
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
