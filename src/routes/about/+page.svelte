<script lang="ts">
	const birthYear = 2006;
	const currentYear = new Date().getFullYear();
	const age = currentYear - birthYear;
</script>

<svelte:head>
	<title>About - Thinh Nguyen</title>
</svelte:head>

<section class="px-6 py-20">
	<div class="mx-auto max-w-4xl">
		<h1 class="mb-8 text-4xl font-bold">About Me</h1>

		<div class="grid gap-12 md:grid-cols-3">
			<div class="md:col-span-2">
				<div class="prose prose-lg dark:prose-invert max-w-none">
					<p class="text-surface-600 dark:text-surface-400">
						I'm a <span class="font-semibold text-primary-600 dark:text-primary-400">{age}-year-old</span>
						passionate full-stack developer
						<span class="font-semibold text-primary-600 dark:text-primary-400">based in Villingen-Schwenningen, Germany</span>,
						with over 5 years of experience building web applications that make a difference.
					</p>

					<p class="mt-4 text-surface-600 dark:text-surface-400">
						My journey began when I was in 5th grade and learned C++ in Highschool. Since then, I've
						honed my skills in various programming languages and frameworks, including JavaScript,
						TypeScript, GoLang
					</p>

					<p class="text-surface-600 dark:text-surface-400">
						I specialize in creating scalable backend systems, intuitive frontend interfaces, and
						streamlined deployment processes. I enjoy collaborating with cross-functional teams to
						deliver high-quality software solutions. In my freetime, I love exploring new
						technologies such as arduino and embedded systems.
					</p>

					<p class="mt-4 text-surface-600 dark:text-surface-400">
						When I'm not coding, you can find me take my camera out and exploring nature, or playing
						video games with friends.
					</p>
				</div>
			</div>

			<div>
				<div class="rounded-xl bg-surface-100 p-6 dark:bg-surface-800">
					<div
						class="mb-4 aspect-square overflow-hidden rounded-lg bg-surface-300 dark:bg-surface-700"
					>
						<!-- Placeholder for profile image -->
						<div
							class="flex h-full items-center justify-center text-surface-500 dark:text-surface-400"
						>
							<img
								src="/images/profile.jpeg"
								alt="Thinh Nguyen"
								class="h-full w-full object-cover object-bottom"
							/>
						</div>
					</div>
					<h3 class="mb-1 font-semibold">Thinh Nguyen</h3>
					<p class="text-sm text-surface-600 dark:text-surface-400">Full Stack Developer</p>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="bg-white px-6 py-20 dark:bg-surface-800/50">
	<div class="mx-auto max-w-4xl">
		<h2 class="mb-12 text-3xl font-bold">Skills & Technologies</h2>

		<div class="grid gap-8 md:grid-cols-2">
			<div>
				<h3 class="mb-4 text-xl font-semibold">Frontend</h3>
				<div class="flex flex-wrap gap-2">
					{#each ['JavaScript', 'TypeScript', 'Svelte', 'React', 'Angular', 'HTML/CSS', 'Tailwind CSS', 'Next.js'] as skill}
						<span
							class="rounded-full bg-primary-100 px-3 py-1 text-sm font-medium text-primary-800 dark:bg-primary-900 dark:text-primary-200"
						>
							{skill}
						</span>
					{/each}
				</div>
			</div>

			<div>
				<h3 class="mb-4 text-xl font-semibold">Backend</h3>
				<div class="flex flex-wrap gap-2">
					{#each ['Node.js', 'GoLang', 'PostgreSQL', 'MongoDB', 'REST APIs', 'GraphQL', 'Docker', 'Linux'] as skill}
						<span
							class="rounded-full bg-accent-100 px-3 py-1 text-sm font-medium text-accent-800 dark:bg-accent-900 dark:text-accent-200"
						>
							{skill}
						</span>
					{/each}
				</div>
			</div>

			<div>
				<h3 class="mb-4 text-xl font-semibold">Tools & Practices</h3>
				<div class="flex flex-wrap gap-2">
					{#each ['Git', 'CI/CD', 'Testing', 'NeoVim', 'Figma', 'VS Code'] as skill}
						<span
							class="rounded-full bg-secondary-100 px-3 py-1 text-sm font-medium text-secondary-800 dark:bg-secondary-900 dark:text-secondary-200"
						>
							{skill}
						</span>
					{/each}
				</div>
			</div>

			<div>
				<h3 class="mb-4 text-xl font-semibold">Soft Skills</h3>
				<div class="flex flex-wrap gap-2">
					{#each ['Problem Solving', 'Communication', 'Team Collaboration', 'Time Management', 'Team Leadership'] as skill}
						<span
							class="rounded-full bg-surface-200 px-3 py-1 text-sm font-medium text-surface-800 dark:bg-surface-700 dark:text-surface-200"
						>
							{skill}
						</span>
					{/each}
				</div>
			</div>
		</div>
	</div>
</section>

<section class="px-6 py-20">
	<div class="mx-auto max-w-4xl">
		<h2 class="mb-12 text-3xl font-bold">Education</h2>

		<div class="space-y-8">
			<div class="rounded-xl border border-surface-200 p-6 dark:border-surface-700">
				<div class="flex flex-col gap-2 md:flex-row md:items-center md:justify-between">
					<div>
						<h3 class="text-xl font-semibold">Abitur</h3>
						<p class="text-surface-600 dark:text-surface-400">Feintechikschule in Schwenningen</p>
					</div>
					<span class="text-sm text-surface-500 dark:text-surface-500">2023 - 2026</span>
				</div>
				<p class="mt-4 text-surface-600 dark:text-surface-400">
					Graduated with honors. Focused on software engineering and electrical engineering.
				</p>
			</div>
		</div>

		<div class="mt-8 space-y-8">
			<div class="rounded-xl border border-surface-200 p-6 dark:border-surface-700">
				<div class="flex flex-col gap-2 md:flex-row md:items-center md:justify-between">
					<div>
						<h3 class="text-xl font-semibold">Highschool</h3>
						<p class="text-surface-600 dark:text-surface-400">Sofia Mathematics Gymnasium</p>
					</div>
					<span class="text-sm text-surface-500 dark:text-surface-500">2018-2023</span>
				</div>
				<p class="mt-4 text-surface-600 dark:text-surface-400">
					Graduated with a focus on mathematics and physics. Participated in various coding
					competitions and tech clubs.
				</p>
			</div>
		</div>
	</div>
</section>
