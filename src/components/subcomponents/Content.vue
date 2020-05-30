<template>
	<div>
		<div class="flex justify-between m-2 items-center">
			<span class="text-left text-base font-bold">
				Home
			</span>
			<!-- Sparkle -->
			<span>
				<svg
					class="h-6 mt-1"
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="#1da1f2"
					viewBox="0 0 24 24"
				>
					<path
						d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"
					></path>
				</svg>
			</span>
		</div>
		<div class="border-t border-b pb-2">
			<div class="flex items-center">
				<img
					class="circle m-2"
					src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
					alt=""
				/>
				<span class="text-gray-500 font-semibold">What's Happening?</span>
			</div>
			<div class="mr-2 ml-12 flex items-center justify-between">
				<div class="flex items-center">
					<span class="pl-1">
						<!-- image -->
						<svg class="h-6" fill="#1da1f2" viewBox="0 0 20 20">
							<path
								d="M4 3a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V5a2 2 0 00-2-2H4zm12 12H4l4-8 3 6 2-4 3 6z"
								clip-rule="evenodd"
								fill-rule="evenodd"
							></path>
						</svg>
					</span>
					<span
						class="ml-1 text-xs font-semibold border-twitter-thick border px-1 inline-block text-twitter-thick tracking-wide"
					>
						GIF
					</span>
					<span class="pl-1">
						<!-- chart -->
						<svg
							style="transform: rotate(90deg);"
							class="svgs"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							stroke="#1da1f2"
							viewBox="0 0 24 24"
						>
							<path
								d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
							></path>
						</svg>
					</span>
					<span class="pl-1">
						<!-- Smile -->
						<svg
							class="svgs"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							stroke="#1da1f2"
							viewBox="0 0 24 24"
						>
							<path
								d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
							></path>
						</svg>
					</span>
				</div>
				<button class="button-class text-sm">
					Tweet
				</button>
			</div>
		</div>
		<div v-for="item in 3" class="border-b m-2 pb-2">
			<div class="flex justify-between items-start">
				<div class=" flex">
					<img
						class="circle"
						src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
						alt=""
					/>
					<span class="mx-2">
						{{ name }}
						<span class="text-gray-500 text-sm">@{{ userName }} 3m</span>
						<div class="text-base">
							Lorem Ipsum has been the industry's standard dummy text ever since
							the 1500s
						</div>
					</span>
				</div>
				<div class="items-center">
					<!-- Dropdown -->
					<svg class="h-6" fill="#a0aec0" viewBox="0 0 20 20">
						<path
							d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
							clip-rule="evenodd"
							fill-rule="evenodd"
						></path>
					</svg>
				</div>
			</div>
			<div class="flex mt-2 justify-around">
				<!-- Comment -->
				<svg
					class="svgs mr-2"
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="#a0aec0"
					viewBox="0 0 24 24"
				>
					<path
						d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"
					></path>
				</svg>
				<!-- Reply -->
				<svg
					class="svgs"
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="#a0aec0"
					viewBox="0 0 24 24"
				>
					<path d="M3 10h10a8 8 0 018 8v2M3 10l6 6m-6-6l6-6"></path>
				</svg>
				<!-- Like -->
				<svg
					class="svgs"
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="#a0aec0"
					viewBox="0 0 24 24"
				>
					<path
						d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
					></path>
				</svg>
				<!-- Upload -->
				<svg
					class="svgs"
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="#a0aec0"
					viewBox="0 0 24 24"
				>
					<path
						d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-8l-4-4m0 0L8 8m4-4v12"
					></path>
				</svg>
			</div>
		</div>
	</div>
</template>
<script type="text/javascript">
export default {
	data() {
		return {
			name: "Kiran",
			userName: "sai_kiran",
		};
	},
};
</script>
<style type="text/css" scoped>
.svgs {
	@apply h-4;
}
</style>
