<script lang="ts">
	// No script needed for static recreation
</script>

<div class="min-h-screen bg-white text-black font-sans px-6 py-8 md:px-10 md:py-10 selection:bg-gray-200">
	<!-- Header -->
	<header class="grid grid-cols-2 md:grid-cols-12 gap-y-4 text-[15px] leading-tight mb-32 md:mb-48 font-normal">
		<div class="col-span-1 md:col-span-3 flex items-center gap-2">
			<svg class="w-5 h-5 text-primary-600" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
				<rect x="4" y="4" width="11" height="11" rx="2" fill="currentColor" />
				<rect x="9" y="9.5" width="10" height="10" rx="2" fill="currentColor" fill-opacity="0.24" />
			</svg>
			<span>Company</span>
		</div>
		
		<div class="col-span-1 md:col-span-2 md:col-start-4">
			<a href="#services" class="hover:opacity-60 transition-opacity">Services</a>
		</div>
		
		<div class="col-span-1 md:col-span-2 md:col-start-6">
			<a href="#approach" class="hover:opacity-60 transition-opacity">Approach</a>
		</div>
		
		<div class="col-span-1 md:col-span-2 md:col-start-10 text-right md:text-left">
			<a href="#clients" class="hover:opacity-60 transition-opacity">Clients</a>
		</div>
		
		<div class="col-span-1 md:col-span-1 md:col-start-12 text-right">
			<a href="#contact" class="hover:opacity-60 transition-opacity">Contact</a>
		</div>
	</header>

	<!-- Hero -->
	<section class="grid grid-cols-1 md:grid-cols-12 mb-32 md:mb-48">
		<div class="col-span-1 md:col-span-9 md:col-start-4 text-[28px] md:text-[32px] leading-[1.15] tracking-tight font-normal">
			<p>
				We help companies formalize their brand through documented guidelines that ensure consistent communication across every touchpoint. From logo usage and color palettes to voice and tone frameworks, we create living systems that empower teams to build with clarity and confidence.
			</p>
		</div>
	</section>

	<!-- Services -->
	<section id="services" class="flex flex-col gap-24 md:gap-32 mb-32">
		<!-- Service 1 -->
		<article class="grid grid-cols-1 md:grid-cols-12">
			<div class="col-span-1 md:col-span-9 md:col-start-4 grid grid-cols-1 md:grid-cols-12 mb-3 text-[15px] gap-y-1 items-baseline">
				<div class="col-span-1 md:col-span-4 font-normal">
					Brand Guidelines
				</div>
				<div class="col-span-1 md:col-span-8 text-gray-400 font-normal">
					Comprehensive documentation covering logo usage, color systems, typography, imagery principles, and application examples across all channels.
				</div>
			</div>
			<div class="col-span-1 md:col-span-9 md:col-start-4 w-full aspect-[16/10] bg-gray-100 overflow-hidden relative group cursor-pointer">
				<img 
					src="/generated/image-marketing-team-reviewing-brand-guideline-1767034515536-0.webp" 
					alt="Brand Guidelines Creation" 
					class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
				/>
				<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent flex items-end justify-start p-8 pointer-events-none">
					<span class="text-white font-normal text-3xl md:text-5xl tracking-tight">Brand Guidelines</span>
				</div>
			</div>
		</article>

		<!-- Service 2 -->
		<article class="grid grid-cols-1 md:grid-cols-12">
			<div class="col-span-1 md:col-span-9 md:col-start-4 grid grid-cols-1 md:grid-cols-12 mb-3 text-[15px] gap-y-1 items-baseline">
				<div class="col-span-1 md:col-span-4 font-normal">
					Visual Identity Systems
				</div>
				<div class="col-span-1 md:col-span-8 text-gray-400 font-normal">
					Structured design systems with logo variations, color palettes, typography hierarchies, and templates for presentations, social, and digital assets.
				</div>
			</div>
			<div class="col-span-1 md:col-span-9 md:col-start-4 w-full aspect-[16/10] bg-primary-50 overflow-hidden relative group cursor-pointer">
				<img 
					src="/generated/image-designer-working-on-visual-identity-syst-1767034518161-1.webp" 
					alt="Visual Identity Systems" 
					class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
				/>
				<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent flex items-end justify-start p-8 pointer-events-none">
					<span class="text-white font-normal text-3xl md:text-5xl tracking-tight">Visual Identity</span>
				</div>
			</div>
		</article>

		<!-- Service 3 -->
		<article class="grid grid-cols-1 md:grid-cols-12">
			<div class="col-span-1 md:col-span-9 md:col-start-4 grid grid-cols-1 md:grid-cols-12 mb-3 text-[15px] gap-y-1 items-baseline">
				<div class="col-span-1 md:col-span-4 font-normal">
					Voice & Tone Framework
				</div>
				<div class="col-span-1 md:col-span-8 text-gray-400 font-normal">
					Explicit voice guidelines grounded in real customer scenarios, with messaging principles and copy examples for every channel and use case.
				</div>
			</div>
			<div class="col-span-1 md:col-span-9 md:col-start-4 w-full aspect-[16/10] bg-gray-100 overflow-hidden relative group cursor-pointer">
				<img 
					src="/generated/image-content-team-collaborating-on-brand-voic-1767034520479-2.webp" 
					alt="Voice & Tone Framework" 
					class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
				/>
				<div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent flex items-end justify-start p-8 pointer-events-none">
					<span class="text-white font-normal text-3xl md:text-5xl tracking-tight">Voice & Tone</span>
				</div>
			</div>
		</article>
	</section>

	<!-- Approach -->
	<section id="approach" class="grid grid-cols-1 md:grid-cols-12 mb-32 md:mb-48">
		<div class="col-span-1 md:col-span-9 md:col-start-4">
			<h2 class="text-[20px] md:text-[24px] font-normal mb-6 tracking-tight">Our Approach</h2>
			<div class="text-[15px] leading-relaxed text-gray-600 space-y-4">
				<p>
					Every engagement begins with discovery—understanding your brand strategy, audience, and the specific challenges your teams face when creating content. We then draft comprehensive guidelines through an iterative process with marketing, product, and leadership stakeholders.
				</p>
				<p>
					Deliverables are provided as living web-based systems or structured Figma libraries, ensuring designers, copywriters, and engineers can reference one source of truth. We extend guidelines into practical templates for presentations, social posts, landing pages, and email—so standards are applied to day-to-day outputs, not just documented in theory.
				</p>
			</div>
		</div>
	</section>

	<!-- Clients -->
	<section id="clients" class="grid grid-cols-1 md:grid-cols-12 mb-32 md:mb-48">
		<div class="col-span-1 md:col-span-9 md:col-start-4">
			<h2 class="text-[20px] md:text-[24px] font-normal mb-6 tracking-tight">Who We Work With</h2>
			<div class="text-[15px] leading-relaxed text-gray-600 space-y-4">
				<p>
					We partner with startups and growth-stage companies that have outgrown ad hoc design and copy practices, as well as mature organizations undergoing repositioning or visual refreshes. Our clients typically need consistent branding but struggle to define clear guidelines for tone, visuals, and messaging across teams.
				</p>
				<p>
					Success is measured by reduced revision cycles, improved internal clarity, and faster, more consistent asset production. We collaborate closely with internal creative, revenue, and product teams, and partner with freelancers or agencies for specialized design and development tasks.
				</p>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer id="contact" class="border-t border-gray-200 pt-6 md:pt-8 text-[13px] leading-relaxed text-gray-400 font-normal">
		<div class="grid grid-cols-1 md:grid-cols-12 gap-y-8">
			<div class="col-span-1 md:col-span-3 flex items-center gap-2">
				<svg class="w-4 h-4 text-primary-600" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
					<rect x="4" y="4" width="11" height="11" rx="2" fill="currentColor" />
					<rect x="9" y="9.5" width="10" height="10" rx="2" fill="currentColor" fill-opacity="0.24" />
				</svg>
				<span>&copy; Company</span>
			</div>

			<div class="col-span-1 md:col-span-2 md:col-start-4 flex flex-col gap-0.5">
				<a href="#" class="hover:text-black transition-colors">LinkedIn</a>
				<a href="#" class="hover:text-black transition-colors">Twitter</a>
				<a href="mailto:hello@company.com" class="hover:text-black transition-colors">Email</a>
			</div>

			<div class="col-span-1 md:col-span-4 md:col-start-6">
				<p class="mb-2">Ready to formalize your brand?</p>
				<a href="mailto:hello@company.com" class="text-black hover:text-primary-600 transition-colors font-normal">Get in touch →</a>
			</div>
		</div>

		<div class="grid grid-cols-1 md:grid-cols-12 mt-12 md:mt-24">
			<div class="col-span-1 md:col-span-6 md:col-start-4 text-gray-400">
				<p>
					We work with companies at every stage—from startups defining their first brand guidelines to established organizations refreshing their visual and verbal identity. Our focus is on creating practical, living systems that reduce confusion and accelerate consistent communication across all teams and channels.
				</p>
			</div>
		</div>
	</footer>
</div>

