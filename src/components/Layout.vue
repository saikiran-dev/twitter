<template>
	<div class="w-full h-screen flex flex-1">
		<div class="w-1/5 border-r"><left-sidebar /></div>
		<div class="w-1/2 border-r"><main-content /></div>
		<div class="w-1/4"><right-sidebar /></div>
	</div>
</template>
<script type="text/javascript">
import LeftSidebar from "./subcomponents/LeftSidebar.vue";
import MainContent from "./subcomponents/Content.vue";
import RightSidebar from "./subcomponents/RightSidebar.vue";
export default {
	components: { LeftSidebar, MainContent, RightSidebar },
};
</script>
