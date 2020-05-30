<template>
	<div class="mx-10 my-2">
		<img class="h-8" src="../../assets/twitter.svg" />
		<ul>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path
						d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
					></path>
				</svg>
				<span>Home</span>
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path d="M7 20l4-16m2 16l4-16M6 9h14M4 15h14"></path>
				</svg>
				Explore
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path
						d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
					></path>
				</svg>

				Notifications
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path
						d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
					></path>
				</svg>
				Messages
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
				</svg>
				Bookmarks
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path
						d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"
					></path>
				</svg>
				Lists
			</li>
			<li class="hover:text-twitter-thick list-items">
				<img
					class="h-6 w-6 rounded-full"
					src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
					alt=""
				/>
				Profile
			</li>
			<li class="hover:text-twitter-thick list-items">
				<svg
					fill="none"
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					stroke="currentColor"
					viewBox="0 0 24 24"
				>
					<path
						d="M8 12h.01M12 12h.01M16 12h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
					></path>
				</svg>
				More
			</li>
		</ul>
		<button class="bg-twitter-thick w-full text-white p-2 rounded-full">
			Tweet
		</button>
	</div>
</template>
<style type="text/css" scoped>
.list-items {
	@apply text-gray-800 text-lg items-center text-left font-semibold my-5 cursor-pointer flex;
}
svg {
	@apply h-6;
}
.list-items svg,
img {
	@apply mr-3;
}
</style>
