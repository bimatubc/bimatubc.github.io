<template>
	<footer id="footer" class="relative bottom-4 left-0 z-20 w-full bg-white dark:bg-gray-900">
		<div class="mx-auto w-full max-w-screen-xl p-4 py-2 lg:py-8">
			<hr class="my-6 border-gray-200 dark:border-gray-700 sm:mx-auto lg:my-8" />

			<div class="sm:flex sm:items-center sm:justify-between">
				<span class="text-sm text-gray-500 dark:text-gray-400 sm:text-center">
					© 2024
					<RouterLink to="/" class="hover:underline">BIMatUBC</RouterLink>. All Rights Reserved.
				</span>

				<!-- Icons -->
				<div class="mt-4 flex sm:mt-0 sm:justify-center">
					<RouterLink
						to="/credits"
						class="ms-5 text-sm text-gray-500 hover:text-gray-900 hover:underline dark:hover:text-white sm:text-center"
						>Credits</RouterLink
					>
					<a href="https://instagram.com/bimatubc">
						<InstagramIcon class="ms-5 text-gray-500 hover:text-gray-900 dark:hover:text-white" />
					</a>
					<a href="https://github.com/bimatubc">
						<GithubIcon class="ms-5 text-gray-500 hover:text-gray-900 dark:hover:text-white" />
					</a>
				</div>
			</div>
		</div>
	</footer>
</template>

<script setup>
import { RouterLink } from 'vue-router'

import InstagramIcon from '@/components/icons/InstagramIcon.vue'
import GithubIcon from '@/components/icons/GithubIcon.vue'
</script>

<style scoped></style>
