<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="For the relentless"
	subtitle="Day zero capital for Europe's deeptech founders building industrial AI, nature tech, and digital infrastructure that transforms industries."
	imageSrc="/generated/image-a-group-of-people-in-a-modern-interior-s.webp"
	callsToAction={[
		{ href: "/contact", label: "Partner with us" },
		{ href: "/portfolio", label: "View portfolio" }
	]}
/>
<LogoScroller
	label="Portfolio companies backed by Europe's deeptech leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/siemens.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bmw.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/sap.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/tum.de/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Build your breakthrough"
	subtitle="Before institutional capital arrives"
	description="We back relentless technical founders at day zero with €500k checks and deep domain expertise. Build your prototype, prove your thesis, and maintain the equity you need for your next round."
	imageSrc="/generated/image-a-satisfied-technical-founder-stands-in-.webp"
	callsToAction={[
		{ href: "/contact", label: "Discuss your venture", variant: "primary" },
		{ href: "/portfolio", label: "Meet our founders", variant: "secondary" }
	]}
/>
