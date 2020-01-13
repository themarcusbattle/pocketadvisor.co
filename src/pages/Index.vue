<template>
	<Layout>

		<div id="hero" class="text-center bg-cover bg-bottom bg-center pt-10">
			<g-image src="~/assets/images/pocket-advisor-logo.png" class="mx-auto mb-12 w-1/2 lg:w-1/4" />
			<h1 class="text-3xl md:text-5xl leading-tight text-white mb-5 font-black">Real Advi¢e. In Real-Time.<br />From a Real Advisor.</h1>
			<p class="text-gray-700 w-2/3 sm:w-1/2 mx-auto text-orange-brand">Imagine someone knowing your financial goals and habits, proactively helping you before a not-so-smart financial situation. That's Pocket Advisor!</p>
			<g-image src="~/assets/images/pocket-advisor-mockup-pay-day.png" class="mx-auto w-xl sm:w-1/3" />
		</div>

		<div id="reasons" class="px-5 py-10 sm:p-24 text-center bg-orange-brand">
			<h2 class="text-4xl mb-5 leading-tight text-white">Private Social Network, Powered by SMS</h2>
			<div class="w-2/3 mx-auto">
				<p class="text-gray-800 w-2/3 mx-auto mb-10">More than proactive financial SMS alerts, Pocket Advisor equips you with a private social network to get the one-on-one support you need to reach your financial goals.</p>
				<p class="text-gray-800 w-2/3 mx-auto mb-10">Most financial tools do not take into account the emotional side of money. They simply tell you what you should or should not do, regardless of how it fits into your lifestyle and what you are currently experiencing. Pocket Advisor aims to be human-friendly and not just send you notifications about your over spending habits, but you help guide you into making decisions that still feel right for you and your lifestyle.</p>
			</div>
			<div class="md:flex text-left">
				<div class="lg:flex-1 bg-white rounded shadow-2xl p-10 mb-10 sm:m-10">
					<h3 class="text-xl mb-10 font-black"><span class="bg-gray-600 w-2 h-2 rounded"></span>Proactive</h3>
					<p class="text-gray-600">Most financial apps now days are reactive. Telling you about what already happened.  Pocket Advisor helps you make the decision before it happens.</p>
				</div>
				<div class="lg:flex-1 bg-white rounded shadow-2xl p-10 mb-10 sm:m-10">
					<h3 class="text-xl mb-10 font-black">Personal</h3>
					<p class="text-gray-600">Pocket Advisor uses its simple two-way messaging feature to learn more about you so that with each tip, insight, or guidance becomes more tailor-made as time goes on.</p>
				</div>
				<div class="lg:flex-1 bg-white rounded shadow-2xl p-10 mb-10 sm:m-10">
					<h3 class="text-xl mb-10 font-black">Practical</h3>
					<p class="text-gray-600">Pocket Advisor is powered by the one thing we know you see every day, SMS. We come to you with valuable but simple tips, so you don’t have to remember to come to us.</p>
				</div>
			</div>
		</div>

		<div class="px-5 py-10  sm:p-24 md:flex bg-gray-200">
			<div class="flex-1">
				<g-image src="~/assets/images/iphone-sms-mockup-2.png" class="mx-auto" />
			</div>
			<div class="flex-1 pt-24">
				<h2 class="text-4xl mb-5">How it works</h2>
				<p class="text-gray-600 mb-10 sm:w-2/3">We’re here to make the decisions with you and not for you. To help you manage &amp; maximize how you use your money.</p>
				<ul class="list-none text-gray-600 sm:w-2/3 mb-20">
					<li class="bg-white p-5 rounded shadow-md mb-8 border-gray-100"><span class="inline-block bg-gray-600 text-white h-10 w-10 text-center pt-1 text-xl mr-5 rounded-full">1</span>Create your profile</li>
					<li class="bg-white p-5 rounded shadow-md mb-8 border-gray-100"><span class="inline-block bg-gray-600 text-white h-10 w-10 text-center pt-1 text-xl mr-5 rounded-full">2</span>Select your prefered group to join</li>
					<li class="bg-white p-5 rounded shadow-md mb-8 border-gray-100"><span class="inline-block bg-gray-600 text-white h-10 w-10 text-center pt-1 text-xl mr-5 rounded-full">3</span>Get proactive real-time advice</li>
				</ul>
				<a class="bg-orange-brand py-3 px-10 rounded text-white hover:bg-gray-700 cursor-pointer" href="https://capitalwize.activehosted.com/f/3">Notify Me of Launch →</a>
			</div>
		</div>

		<div class="px-5 py-10 sm:p-24 text-center">
			<h2 class="text-4xl mb-10">Pricing</h2>
			<table class="table-fixed mx-auto w-full md:w-2/3 shadow-md rounded mb-20 overflow-x sm:overflow-auto">
				<thead>
					<tr>
						<th class="w-1/3 px-4 py-10 border rounded">
							<h3 class="text-xl mb-2"></h3>
							<span class="text-orange-brand"></span>
						</th>
						<th class="w-1/3 px-4 py-10 border rounded">
							<h3 class="text-xl mb-2">Lite</h3>
							<span class="text-orange-brand">Free</span>
						</th>
						<th class="w-1/3 px-4 py-10 border rounded">
							<h3 class="text-xl mb-2">Standard</h3>
							<span class="text-orange-brand">$4.99</span>
						</th>
						<th class="w-1/3 px-4 py-10 border rounded">
							<h3 class="text-xl mb-2">Pro</h3>
							<span class="text-orange-brand">$9.99</span>
						</th>
					</tr>
				</thead>
				<tbody class="text-gray-600">
					<tr>
						<td class="border-r px-4 py-4">Money Mindset Advice - Real-time advice designed to put you in the right head-space to align your behaviors with your goals.</td>
						<td class="border-r px-4 py-4">X</td>
						<td class="border-r px-4 py-4">X</td>
						<td class=" px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Smart Spender - Real-time guidance on overall smart spending decisions</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4">X</td>
						<td class="px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Super Saver - Real-time guidance on helping you save more money</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4">X</td>
						<td class=" px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Intelligent Investor - Real-time guidance on investing</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class=" px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Business Boss - Real-time advice designed exclusively for business owners ready level up</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class=" px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Delete Your Debt - Advice designed to help you get out of debt the right way, saving you time and money.</td>
						<td class="border-r px-4 py-2 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class=" px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Food For Thought - Real-time Guidance on preventing you from spending too much money on food</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Love and Money - Real-time advice designed specifically for couples</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Family First - Real-time advice designed specifically for families</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="px-4 py-4">X</td>
					</tr>
					<tr>
						<td class="border-r px-4 py-4">Credit Hacks - Real-time advice to help you improve and maximize your credit</td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="border-r px-4 py-4 bg-gray-100"></td>
						<td class="px-4 py-4">X</td>
					</tr>
				</tbody>
			</table>
			<a class="bg-orange-brand py-3 px-10 rounded text-white inline-block hover:bg-gray-700 cursor-pointer" href="https://capitalwize.activehosted.com/f/3">Notify Me of Launch →</a>
		</div>

		<div class="p-16 bg-gray-900 text-center">
			<g-image src="~/assets/images/pocket-advisor-logo.png" class="mx-auto mb-4 w-1/2 lg:w-1/4" />
			<p class="text-gray-700">&copy; 2019. <a href="http://georgeacheampong.com/" class="text-orange-400">Acheampong Enterprises, LLC</a>. All rights reserved. Powered by <a href="https://tekst.co" class="text-orange-400 hover:text-gray-100">Tekst</a>.</p>
		</div>
	</Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Proactive financial SMS alerts'
  }
}
</script>

<style>
	#hero {
		/* background-color: #0074D9; */
		background-image: url(~@/assets/images/pa-blue-grid-background.jpg);
		/* height: 800px; */
	}

	#reasons {
		background-image: url(~@/assets/images/woman-typing-on-iphone.jpg);
	}
	.bg-orange-brand {
		background-color: #F7941E;
	}
	.text-orange-brand {
		color: #F7941E;
	}
</style>
