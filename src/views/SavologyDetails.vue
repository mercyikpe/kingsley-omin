<template>
	<main class="bg-white relative font-Graphik">
		<div class="container mx-auto px-4 lg:px-0 relative z-40 lg:pt-6 relative">
			<Header />
		</div>

		<section class="lg:pb-12 lg:pt-12">
			<div class="items-center flex justify-center w-full px-2 md:px-8 lg-px-24 xl:px-32">
				<img class="h-auto" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308307/kingsley%20omin/SAVOLOGY-banner.png" alt="Project Savology">
			</div>

			<div class="absolute right-0 top-0 mt-24 pt-24 mr-8 hidden lg:block">
				<Icon
						name="light-switch"
						class="cursor-pointer hover:opacity-75 pb-8 pt-2"
						title="switch"
						width="30"
				/>
				<p class="transform -rotate-90 mt-4 font-medium text-blue-800 -ml-8">Switch View</p>
			</div>
		</section>

		<section id="savology-paragraph" class="container mx-auto text-blue-600 text-base px-4">
			<div class="mt-12 md:mt-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Overview</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					Savology is a mobile application that enables parents and guardians to save money specifically for their children’s university education.
				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">The Challenge</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					The costs of higher education all over the world continue to rise while the possibilities of affording this education continue to
					decrease. Even with help from parents or guardians many Nigerians still struggle to meet the financial demands of world-class
					universities. Meaningful university education now seems to be within the reach of only individuals from highly privileged backgrounds
					or those fortunate enough to attain scholarships.
					<br>
					The primary goal of this project is to empower parents and guardians to be in a much better position to afford university.
					We figured that if they had the option to start saving towards this goal. as early as possible then their chances of meeting
					the financial requirements would improve exponentially. Ultimately we want anyone responsible for any amount of children to be
					able to prudently save towards their university education.
				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Goals & Objectives</h3>
				<ul class="mt-4 md:mt-8 lg:mt-10">
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						To help parent plan for their children’s university education.</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						To re-install confidence and ease some of the problems that comes with parenting.</li>
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						To achieve a product with minimal UI designs, easy navigation and fewer user actions.</li>
				</ul>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Research</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					With a better understanding of the problem, I began my research with a competitive analysis to understand the landscape
					I was venturing into. I find information on existing apps, the apps people liked versus those they didn’t like and I got
					acquainted with other available products to understand their features and USP’s. With my target audience being guardians,
					parents and Intending parents, I conducted user research by creating some interview questions to better understand their
					behaviour and pain point.
				</p>

				<h4 class="text-xl font-semibold text-blue-600 mt-6">Some of the research findings</h4>
				<ul class="mt-4 md:mt-8 lg:mt-10">
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						People are willing to spend a considerable amount of money on their children’s university education due to perceptions
						of its value, however, most persons simply cannot afford to do so.
					</li>
					<li class="my-4">
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						They welcome the idea of having an application that helps them save but are more concerned about the stability and
						safety of their money due to past experiences. As such they require an assurance of security as well as restrictions to
						help them avoid the temptation of withdrawing funds for something else.
					</li>
					<li>
						<Icon
								name="bullet"
								class="align-bottom mr-2 md:mr-4"
								title="bullet"
						/>
						Rather than just saving the money and cashing-out the same amount people prefer to invest and get interested in return.
						The ability to save and invest should be automated.
					</li>
				</ul>

			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">User Persona</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					These research questions gave me better insight into my intended audience and helped me to identify their pain points.
					To give personality to my research I created a user persona
				</p>

				<div class="w-full mt-10">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308306/kingsley%20omin/savology-user-persona.png" alt="Project Savology">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">User Flow</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					The user flow diagram gives an insight into how things are organized inside of the application and it also
					makes it easier to continue the design process.
				</p>

				<div class="w-full mt-10">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308306/kingsley%20omin/savology-userflow.png" alt="Project Savology">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Wire Frames</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					I usually get attached to a single idea while sketching and creating a wireframe, but for this project,
					I tried to detach myself from that mindset and instead adopted multiple layouts. I found inspiration from
					Dribbble and other platforms. Wireframes are easier and faster ways of representing and testing your ideas,
					they are a low fidelity representation of a product, it can be tested with users so that changes can quickly
					be made if any. This was done to evaluate the idea and to see if it works and solves the problem, luckily this
					allowed me to make some improvements
				</p>

				<div class="p-8 md:p-12 lg:p-24 bg-gray-100 rounded-lg mt-10">
					<div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-8 gap-8 py-6">
						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-1.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-2.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-3.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-4.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-5.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-6.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-7.png" alt="Savology wireframe">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597394554/kingsley%20omin/savology-wireframe/savology-wf-8.png" alt="Savology wireframe">
						</div>
					</div>
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Visual Design</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					With my potential users being guardians, parents and intending parents I wanted a design that made them feel good and relaxed.
					For the product personality, I had three key things in mind; a clean design, smart & elegant logo and novelty. I tried to stick
					to those while designing the visuals. These concepts were adopted into the logo design
				</p>

				<div class="w-full mt-8">
					<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308306/kingsley%20omin/savology-visual-design.png" alt="Project Savology">
				</div>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-3xl font-semibold text-blue-600">Home Sreen</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					The home screen of the app is the first screen a user sees after logging in. This screen contains all the primary actions
					of the app, this helps to ease navigation to different screens. The home screen displays the user’s total balance and a
					user can easily create an education trust fund. Each screen had multiple iterations before I decided on the final design,
					and the home screen was not an exception. From the initial design, the home screen had a beautiful pop-up design (which I loved),
					nudging a user to add a debit card. At first, I thought this was a brilliant idea, but after testing the idea I discovered that
					this was irritating to some users and hence could cause them to abandon the app.
					A typical user wants to explore any application first and get comfortable with it before they decide to act, and the design was
					more or less imposing action on them. With this new knowledge, I decided to remove the pop up nudging a user to add a debit card.
					So from the new design, a user is only asked to add a debit card when He Or She is trying to save money on a trust fund they created.
				</p>
			</div>

			<div class="my-12 md:my-20">
				<h3 class="text-2xl md:text-2xl md:text-3xl font-semibold text-blue-600">Creating an Education Trust Fund</h3>
				<p class="mt-4 md:mt-8 lg:mt-10">
					From the home page, a user can create either a dollar or a naira education trust funds in a few simple steps. The process
					involves a user clicking either one and customizing it by naming it after the child he or she is saving for and then selects
					if he/she wants the savings on the trust fund to be automated or not, if yes a user set how often he wants that to happen,
					could be daily, weekly or monthly and also set the maturity period (how long user want to save for).
					On the payment method, a user has the option of adding a new debit card or selects from the one he or she had saved earlier
					on the system and proceed to successfully create an education trust fund for his or her child.
				</p>

				<div class="p-8 md:p-12 lg:p-24 bg-purple-200 rounded-lg mt-10">
					<div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8 py-6">
						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-1.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-2.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-3.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-4.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-5.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-6.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-7.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-8.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-9.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-10.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-11.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-12.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-13.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-14.png" alt="Project Savology">
						</div>

						<div>
							<img class="h-auto w-full" src="https://res.cloudinary.com/mercyikpe/image/upload/v1597308304/kingsley%20omin/savology-15.png" alt="Project Savology">
						</div>
					</div>
				</div>
			</div>


			<div class="my-16">
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

	export default {
		name: "savology",
		components: {Footer, Icon, Header}
	}
</script>

<style scoped>
	.list-disc {}
</style>
