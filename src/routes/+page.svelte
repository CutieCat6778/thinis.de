<svelte:head>
	<title>Your Name - Portfolio</title>
</svelte:head>

<section class="px-6 py-20 md:py-32">
	<div class="mx-auto max-w-4xl text-center">
		<h1 class="mb-6 text-4xl font-bold tracking-tight md:text-6xl">
			Hi, I'm <span class="text-primary-600 dark:text-primary-400">Thinh Nguyen</span>
		</h1>
		<p class="mb-8 text-xl text-surface-600 md:text-2xl dark:text-surface-400">
			A Full-Stack & Embedded Developer
		</p>
		<p class="mx-auto mb-10 max-w-2xl text-lg text-surface-600 dark:text-surface-400">
			I specialize in creating dynamic web applications and embedded systems that deliver seamless
			user experiences. With a passion for coding and problem-solving, I bring ideas to life through
			innovative technology solutions.
		</p>
		<div class="flex flex-wrap justify-center gap-4">
			<a
				href="/work"
				class="rounded-lg bg-primary-600 px-6 py-3 font-semibold text-white transition-colors hover:bg-primary-700"
			>
				View My Work
			</a>
			<a
				href="/contact"
				class="rounded-lg border border-surface-300 px-6 py-3 font-semibold transition-colors hover:bg-surface-100 dark:border-surface-700 dark:hover:bg-surface-800"
			>
				Get in Touch
			</a>
		</div>
	</div>
</section>

<section class="bg-white px-6 py-20 dark:bg-surface-800/50">
	<div class="mx-auto max-w-6xl">
		<h2 class="mb-12 text-center text-3xl font-bold">What I Do</h2>
		<div class="grid gap-8 md:grid-cols-3">
			<div class="rounded-xl border border-surface-200 p-6 dark:border-surface-700">
				<div
					class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-primary-100 dark:bg-primary-900"
				>
					<svg
						class="h-6 w-6 text-primary-600 dark:text-primary-400"
						fill="none"
						stroke="currentColor"
						viewBox="0 0 24 24"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
						/>
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold">Frontend Development</h3>
				<p class="text-surface-600 dark:text-surface-400">
					Building responsive and interactive user interfaces with modern frameworks like Svelte,
					React, and Vue.
				</p>
			</div>
			<div class="rounded-xl border border-surface-200 p-6 dark:border-surface-700">
				<div
					class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-accent-100 dark:bg-accent-900"
				>
					<svg
						class="h-6 w-6 text-accent-600 dark:text-accent-400"
						fill="none"
						stroke="currentColor"
						viewBox="0 0 24 24"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2"
						/>
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold">Backend Development</h3>
				<p class="text-surface-600 dark:text-surface-400">
					Creating robust APIs and server-side applications with Node.js, Python, and various
					databases.
				</p>
			</div>
			<div class="rounded-xl border border-surface-200 p-6 dark:border-surface-700">
				<div
					class="mb-4 flex h-12 w-12 items-center justify-center rounded-lg bg-secondary-100 dark:bg-secondary-900"
				>
					<svg
						class="h-6 w-6 text-secondary-600 dark:text-secondary-400"
						fill="none"
						stroke="currentColor"
						viewBox="0 0 24 24"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8V4m0 16v-4m8-4h4m-16 0H4m12.364-5.364l2.828-2.828m-12.728 0l2.828 2.828m12.728 12.728l-2.828 2.828m-12.728 0l2.828-2.828"
						/>
					</svg>
				</div>
				<h3 class="mb-2 text-xl font-semibold">Embedded</h3>
				<p class="text-surface-600 dark:text-surface-400">
					Designing and programming embedded systems using C/C++ and microcontrollers for IoT
					applications.
				</p>
			</div>
		</div>
	</div>
</section>

<section class="px-6 py-20">
	<div class="mx-auto max-w-4xl text-center">
		<h2 class="mb-6 text-3xl font-bold">Let's Work Together</h2>
		<p class="mb-8 text-lg text-surface-600 dark:text-surface-400">
			Have a project in mind? I'd love to hear about it. Let's discuss how we can bring your ideas
			to life.
		</p>
		<a
			href="/contact"
			class="inline-block rounded-lg bg-primary-600 px-8 py-4 font-semibold text-white transition-colors hover:bg-primary-700"
		>
			Start a Conversation
		</a>
	</div>
</section>
