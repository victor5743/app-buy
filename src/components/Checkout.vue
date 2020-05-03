<template>
	<div class="block p-8 sm:p-0 sm:flex my-16 mx-auto max-w-3xl rounded-lg shadow-lg">
		<!-- Left panel -->
		<LeftPanel />

		<!-- Right panel -->
		<RightPanel />
	</div>
</template>

<script>
import LeftPanel from './LeftPanel.vue';
import RightPanel from './RightPanel.vue';

export default {
	components: {
		LeftPanel,
		RightPanel,
	},
};
</script>
