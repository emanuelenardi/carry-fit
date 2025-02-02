<script lang="ts">
	import { ArrowLeft } from 'lucide-svelte';
	import { base } from '$app/paths';

	const lastUpdated = new Date('2025-01-13');
</script>

<div class="min-h-screen px-2 py-8 sm:px-4">
	<div class="mx-auto max-w-3xl">
		<div class="mb-8">
			<a
				href="{base}/"
				class="inline-flex items-center gap-2 rounded-lg bg-white/95 px-4 py-2 text-sky-700 shadow-md ring-1 ring-sky-100 transition-colors hover:bg-sky-50"
			>
				<ArrowLeft class="h-4 w-4" />
				<span>Back to CarryFit</span>
			</a>
		</div>

		<div class="rounded-xl bg-white/95 p-6 shadow-xl ring-1 ring-sky-100">
			<h1
				class="mb-6 bg-gradient-to-r from-blue-700 to-sky-500 bg-clip-text text-3xl font-bold text-transparent sm:text-4xl"
			>
				Privacy Policy
			</h1>

			<div class="prose prose-sky max-w-none space-y-8">
				<p class="text-sm text-sky-600">Last updated: {lastUpdated.toLocaleDateString()}</p>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Overview</h2>
					<p class="text-sky-800">
						CarryFit ("we", "us", or "our") is committed to protecting your privacy. This Privacy
						Policy explains how we collect, use, and safeguard your information when you use our
						website.
					</p>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Information We Collect</h2>
					<p class="text-sky-800">
						We use analytics services (PostHog and Plausible) to collect anonymous usage data that
						helps us understand how visitors interact with our website. This information includes:
					</p>
					<ul class="list-disc space-y-1 pl-5 text-sky-800">
						<li>Pages visited</li>
						<li>Time spent on the website</li>
						<li>Browser type and version</li>
						<li>Operating system</li>
						<li>Anonymous interaction data (e.g., button clicks, form submissions)</li>
					</ul>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">
						How We Use Your Information
					</h2>
					<p class="text-sky-800">The collected data is used solely for:</p>
					<ul class="list-disc space-y-1 pl-5 text-sky-800">
						<li>Analyzing website usage patterns</li>
						<li>Improving user experience</li>
						<li>Identifying and fixing technical issues</li>
						<li>Understanding which features are most valuable to users</li>
					</ul>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Data Storage and Privacy</h2>
					<p class="text-sky-800">
						All analytics data is processed by our analytics providers (PostHog and Plausible). We
						use memory-only storage for analytics tracking, which means:
					</p>
					<ul class="list-disc space-y-1 pl-5 text-sky-800">
						<li>No cookies are used for tracking</li>
						<li>No tracking data is stored in your browser's local storage</li>
						<li>All tracking data is cleared when you close the website</li>
						<li>We do not collect or store any personally identifiable information</li>
					</ul>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Your Rights</h2>
					<p class="text-sky-800">
						You have the right to opt out of analytics tracking. Since we don't use cookies, you can
						use your browser's built-in privacy features or extensions to block analytics scripts if
						you wish to opt out.
					</p>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Changes to This Policy</h2>
					<p class="text-sky-800">
						We may update this Privacy Policy from time to time. We will notify you of any changes
						by posting the new Privacy Policy on this page.
					</p>
				</div>

				<div class="space-y-4">
					<h2 class="text-xl font-semibold text-sky-900 sm:text-2xl">Contact Us</h2>
					<p class="text-sky-800">
						If you have any questions about this Privacy Policy, please contact us at <a
							href="mailto:alexey.maltsev.work@gmail.com"
							class="font-medium text-blue-600 hover:text-blue-800 hover:underline"
							>alexey.maltsev.work@gmail.com</a
						>.
					</p>
				</div>
			</div>
		</div>
	</div>
</div>
