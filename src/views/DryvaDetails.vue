<template>
	<main class="bg-white dark:bg-black relative font-Graphik">
		<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">
			<Header />
		</div>

		<section class="pt-8 lg:pb-12 lg:pt-12">
			<div class="items-center flex justify-center w-full px-2 md:px-8 lg-px-24 xl:px-32">
				<img class="h-auto" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312633/kingsley%20omin/Dryva-banner.png" alt="Project Dryva">
			</div>

			<div class="absolute right-0 top-0 mt-24 pt-24 mr-12 hidden lg:block">
				<DarkModeToggle />
				<p class="transform -rotate-90 mt-4 font-medium text-blue-800 dark:text-white -ml-8" @click="alert">Switch View</p>
			</div>
		</section>

		<section id="savology-paragraph" class="container mx-auto text-blue-600 dark:text-white text-base px-4">
			<div class="mt-12 md:mt-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Overview</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					Dryva is a professional hiring service that connects trusted drivers to clients who already own vehicles but require drivers.				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">The Challenge</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					For a city like Lagos, ride-hailing apps are essential, they help to ease the stresses of daily commutes and provide an alternative to public transportation. However, current ride-hailing operations inadvertently leave the needs of one core demographic unmet. This underserved market is made up of individual car owners who prefer to occasionally be driven by a driver — as a means of coping with the stressful lifestyle associated with large urban cities, such as traffic congestion, and long commute times.
					<br>
					Most times people don’t intend to hire a driver for an extended period, they just need one for a few days or weeks, and neither do they intend to become dependent on ride-hailing services for all their transportation needs. Thus, a platform that provided for this demographic in particular was necessary.
				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Goals & Objectives</h3>
				<ul class="mt-4 md:mt-8 lg:mt-10">
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						To help improve a user’s lifestyle by taking away the stress of finding short term drivers.
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						Easy and flexible hiring process.
					</li>
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						Minimal UI designs with easy navigation and fewer user actions.
					</li>
				</ul>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Team</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					The design team consisted of myself and @namnsoukpanah. We had three weeks to create the designs that will help our users reach this goal.
				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Research</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					With a better understanding of the product, we began the research with the assumption that the user base would be mostly the middle-class individuals with jobs and other life activities that required them to commute often. After developing a research plan that included brainstorming with the team, creating and deploying a survey and conducting a series of interviews, we set out to conduct the user research. We started by interviewing some friends who were car owners.				</p>

				<h4 class="text-xl font-semibold text-blue-600 dark:text-white mt-6">Some research questions we asked</h4>
				<ul class="mt-4 md:mt-8 lg:mt-10">
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						What does your typical day look like?
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						How often do you commute? and how many hours do you spend commuting?
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						What would you like to do while commuting?
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						What issues do you have driving yourself?
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						Would you love to be driven sometimes?
					</li>
				</ul>

				<p class="mt-4 md:mt-8 lg:mt-10">
					The research was to help us gauge our potential users’ pain points as regards having to drive themselves on their daily commute, and consequently how best to tackle them. To give personality to my research I created a user persona.
				</p>

			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">User Persona</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					Based on the findings from the research and interviews, we were able to create a user persona to have a more critical understanding of the user.
				</p>

				<div class="w-full mt-10">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312623/kingsley%20omin/Dryva-persona.png" alt="Project Dryva">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">User Flow</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					From all the information gathered, we created a user flow for the product. We aimed to help define the likely steps a user might take through various pages and actions on the app to complete their goal. Not only did this help us minimize user actions, it also helped us to deliver a better experience in the most effective way possible.
				</p>

				<div class="w-full mt-10">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312623/kingsley%20omin/Dryva-userflow.png" alt="Project Dryva">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Wire Frames</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					After brainstorming on all the outlined app features, wireframes were created to give a clearer understanding of the project structure to both the client and the development team, and likewise to create room for any adjustments. A wireframe is a visual representation of a user interface that shows the skeletal framework of the app. It is a faster method of planning the information architecture of the app transition.
				</p>

				<div class="p-8 md:p-12 lg:p-24 bg-gray-100 rounded-lg mt-10">
					<div class="grid grid-cols-2 md:grid-cols-5 gap-8 py-6">
						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-1.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-2.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-3.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-4.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-5.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-6.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-7.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-8.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-9.png" alt="Dryva wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597395043/kingsley%20omin/dryva-wireframe/dryva-wf-10.png" alt="Dryva wireframe">
						</div>


					</div>
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600 dark:text-white">Visual Design</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					The next plan of action was to create colour palettes and typography that would help communicate the brand’s identity and also give the product an exciting feel.
				</p>

				<div class="w-full mt-8">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312623/kingsley%20omin/Dryva-visual-design.png" alt="Project Dryva">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<p class="mt-4 md:mt-8 lg:mt-10">
					Once the design structure was approved, we moved into full swing with the designs. In an attempt to attract as many users as possible, We tried to use elements and icons similar to popular ride-hailing applications just to help ease navigation and we also took some time to learn and understand what it means to have a strong visual design, making sure the product was usable and appealing to our audience.
					We paid particular attention to the app’s usability, to ensure that users could navigate through with ease and perform actions with minimal effort. We delivered the final designs to the developers on schedule. Once we handed off the final designs, we were on stand-by for development support while they finished building the app. During the development process, we were able to catch missed interactions and clarify the flow of pages.
				</p>

				<div class="p-8 md:p-12 lg:p-24 bg-yellow-100 rounded-lg mt-10">
					<div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8 py-6">
						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-1.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-2.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-3.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-4.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-5.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-6.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-7.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-8.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-9.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-10.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-11.png" alt="Project Dryva screen">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597312621/kingsley%20omin/Dryva-12.png" alt="Project Dryva screen">
						</div>

					</div>
				</div>
			</div>


			<div class="my-16 hidden">
				<a
						href="https://www.figma.com/proto/fxgWKYHKuPLPIc8uh1s1Dg/SAVOLOGY?node-id=196%3A11118&viewport=579%2C421%2C0.03894153609871864&scaling=min-zoom"
						class="underline sm:font-xl text-yellow-600 mt-8 font-medium">
					Click to view prototype
				</a>
			</div>
		</section>

		<Footer />
	</main>
</template>

<script>
	import Icon from "../assets/icons/Icon";
	import Header from "../components/Header";
	import Footer from "../components/Footer";
		import DarkModeToggle from "../components/DarkModeToggle";

	export default {
		name: "dryva",
		components: {DarkModeToggle, Footer, Icon, Header}
	}
</script>

<style scoped>
	.list-disc {}
</style>
