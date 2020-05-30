<template>
	<div class="my-1 h-screen mx-2 items-center">
		<div class="bg-gray-300  items-center rounded-full flex py-2 px-3">
			<svg
				class="h-4 mr-1"
				fill="none"
				stroke-linecap="round"
				stroke-linejoin="round"
				stroke-width="2"
				stroke="#a0aec0"
				viewBox="0 0 24 24"
			>
				<path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
			</svg>
			<input
				class="bg-gray-300 overflow-hidden appearance-none w-full font-semibold text-sm leading-tight focus:outline-none focus:shadow-outline"
				id="username"
				type="text"
				placeholder="Search Twitter"
			/>
		</div>
		<div class="h-full my-2 rounded-lg bg-gray-200">
			<div
				class="flex items-center px-2 py-2 border-b border-gray-400 justify-between"
			>
				<span class="font-bold">Trends For You</span>
				<span>
					<svg
						class="h-4 mt-1"
						fill="none"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						stroke="#1da1f2"
						viewBox="0 0 24 24"
					>
						<path
							d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
						></path>
						<path d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
					</svg>
				</span>
			</div>
			<div class="my-2 border-b px-2 py-2">
				<span class="text-sm block text-gray-500 font-semibold tracking-tight">
					Trending worldwide
				</span>
				<span class="text-sm block text-gray-800 font-bold tracking-tight">
					#BreakingNews
				</span>
				<span class="text-sm block text-gray-500 font-semibold tracking-tight">
					127K Tweets
				</span>
				<span class="text-sm block text-gray-500 font-semibold tracking-tight">
					5,094 people are tweeting about this
				</span>
			</div>
		</div>
	</div>
</template>
