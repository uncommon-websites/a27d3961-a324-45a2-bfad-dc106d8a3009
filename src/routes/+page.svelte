<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
	
	// Icons
	import IconZap from "~icons/lucide/zap";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconUsers from "~icons/lucide/users";
	import IconDollarSign from "~icons/lucide/dollar-sign";
	import IconSparkles from "~icons/lucide/sparkles";
	import IconRefreshCw from "~icons/lucide/refresh-cw";
</script>

<CustomerCardHero
	title="High-converting landing pages for YC's fastest-growing startups"
	subtitle="Ship your landing page in days, not weeks. Conversion-optimized design patterns meet rapid execution."
	centered={true}
	customers={[
		{
			name: "Sarah Chen",
			position: "Founder, Mooodboard",
			imageSrc: "/generated/image-candid-environmental-portrait-of-a-profe.webp"
		},
		{
			name: "Marcus Rivera",
			position: "CEO, Hillclimb",
			imageSrc: "/generated/image-candid-environmental-portrait-of-a-profe.webp"
		},
		{
			name: "Emily Patel",
			position: "Co-founder, Imagine AI",
			imageSrc: "/generated/image-candid-documentary-style-portrait-of-a-p.webp"
		},
		{
			name: "David Kim",
			position: "Founder, Clarum",
			imageSrc: "/generated/image-candid-environmental-portrait-of-a-profe.webp"
		},
		{
			name: "Jessica Wong",
			position: "CEO, Stealth Startup",
			imageSrc: "/generated/image-candid-documentary-portrait-of-a-profess.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by YC's fastest-growing startups"
	mode="dark"
	logoUrls={[
		'https://cdn.brandfetch.io/retool.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/webflow.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/idgEcYrCaG/w/400/h/400/logo',
		'https://cdn.brandfetch.io/idmfGfVgqd/w/400/h/400/logo'
	]}
/>

<Summary
	text="Semiotic delivers high-converting landing pages specifically for YC-backed startups who need to launch fast. We combine proven conversion patterns from analyzing top performers with rapid two-week delivery, so non-technical founders can validate product-market fit without expensive agency timelines or design resources."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Deshmukh",
			position: "Founder",
			company: "Velora AI",
			quote:
				"We shipped our landing page in 5 days instead of the 6 weeks our agency quoted. That speed let us launch before Demo Day and secure our seed round. The conversion-optimized patterns they used drove 3x more signups than our previous MVP page.",
			image: "/generated/image-candid-environmental-portrait-of-a-confi.webp"
		},
		{
			name: "Jamal Richardson",
			position: "Co-founder & CEO",
			company: "Nucleus",
			quote:
				"Fixed pricing saved us $15K compared to agency quotes, and the quality was honestly better. For a pre-seed startup watching every dollar, that was make-or-break. We redirected those savings into our first engineering hire.",
			image: "/generated/image-candid-environmental-headshot-of-a-confi.webp"
		},
		{
			name: "Arjun Mehta",
			position: "Founder",
			company: "Compass Analytics",
			quote:
				"Their conversion patterns are based on data from top performers, not guesswork. Our sign-up rate jumped from 2% to 8% after launch. Instead of A/B testing for months, we started with a page that actually converts.",
			image: "/generated/image-candid-documentary-portrait-of-a-confide.webp"
		}
	]}
/>

<Features
	title="Built for speed, optimized for conversion"
	subtitle="Everything you need to ship a high-converting landing page that validates product-market fit fast"
	features={[
		{
			title: "Ship in under 2 weeks",
			description:
				"Fixed 2-week delivery from kickoff to launch. No agency timelines, no endless revisions, just rapid execution when you need it most.",
			icon: IconZap,
			iconClass: "text-[#22D3EE]"
		},
		{
			title: "Conversion-optimized patterns",
			description:
				"Design patterns analyzed from top-performing landing pages. Every element is crafted to drive signups and validate your product-market fit.",
			icon: IconTrendingUp,
			iconClass: "text-[#6366F1]"
		},
		{
			title: "YC ecosystem expertise",
			description:
				"We speak your language because we live in your world. Built specifically for YC founders who need to move fast and prove traction.",
			icon: IconUsers,
			iconClass: "text-[#8B5CF6]"
		},
		{
			title: "Fixed pricing, zero surprises",
			description:
				"One price, no hidden costs, no scope creep. Get agency-quality work without the agency bloat or unpredictable invoices.",
			icon: IconDollarSign,
			iconClass: "text-[#22D3EE]"
		},
		{
			title: "Metalab-quality design",
			description:
				"Polished, sophisticated aesthetics inspired by design leaders. Your landing page will look like it came from a top-tier agency.",
			icon: IconSparkles,
			iconClass: "text-[#6366F1]"
		},
		{
			title: "Rapid post-launch iteration",
			description:
				"Launch isn't the end, it's the beginning. Quick iteration cycles help you optimize conversion rates as you learn from real users.",
			icon: IconRefreshCw,
			iconClass: "text-[#8B5CF6]"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Launch your high-converting landing page in under 2 weeks"
	subtitle="Your YC batch is moving fast. Don't fall behind."
	description="Every day without a landing page is a day you can't validate product-market fit or capture leads. Book a 30-minute call this week and ship your conversion-optimized page before your next investor meeting."
	imageSrc="/generated/image-a-candid-documentary-style-photo-of-a-di.webp"
	callsToAction={[
		{
			href: "https://cal.com/uncommon/30min",
			label: "Book your 30-minute call",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See our process",
			variant: "secondary"
		}
	]}
/>
