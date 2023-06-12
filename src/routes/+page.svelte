<svelte:head>
	<title>Cuba</title>
	<meta name="description" content="Cuba" />
</svelte:head>

<h1>Cuba</h1>

<p class="indent">
	I tried to compile here a list of anecdotes that happened to me during my two-week vacation in
	Cuba. Most of the work displayed here is given as-is, with very few edits. Some sentences were
	adjusted a bit because they didn't mean anything but the rest is <i>raw</i>: I am no writer so the
	format and wording will not be the best. However, I wanted to give a glimpse of how I experienced
	this very first trip on my own.
</p>

<div class="articles">
	<ul>
		<li class="article">
			<div class="header">
				<a href="/fabrica" class="article-link">Fabrica</a>
				<span class="last-edited">Last edited: 22/05/23</span>
			</div>

			<span class="article-info">La Havana &middot; 30/04/2023 &middot; 10pm</span>
			<p class="article-preview">
				I explored a famous night club during my second night (and birthday) in Cuba: The Cuban Art
				Factory (Fabrica de Arte), which is museum with multiple music scenes.
			</p>
		</li>

		<li class="article">
			<div class="header">
				<a href="/doble-taxi" class="article-link">Doble Taxi</a>
				<span class="last-edited">Last edited: 27/05/23</span>
			</div>
			<span class="article-info">La Havana &middot; 01/05/2023 &middot; 5:30am</span>
			<p class="article-preview">
				I got into a bit of trouble finding the bus station to go to Vi&ntilde;ales and was forced
				to go in a three-wheeled taxi.
			</p>
		</li>

		<li class="article">
			<div class="header">
				<a href="/australian-grandpa" class="article-link">Australian Grandpa</a>
				<span class="last-edited">Last edited: 04/06/23</span>
			</div>

			<span class="article-info">Vi&ntilde;ales &middot; 01/05/2023 &middot; 12:00pm</span>
			<p class="article-preview">
				Upon my arrival at my second destination, I meet Antonio, an Australian man at least thrice
				my age. We start an adventure in the countryside and he tells me about his very impressive
				travel stories.
			</p>
		</li>

		<li class="article">
			<div class="header">
				<a href="/cow-viewpoint" class="article-link">Cow Viewpoint</a>
				<span class="last-edited">Last edited: 12/06/23</span>
			</div>

			<span class="article-info">Vi&ntilde;ales &middot; 01/05/2023 &middot; 6:00pm</span>
			<p class="article-preview">
				After a long day of exploration, I infiltrated myselft in a fancy all-inclusive hotel that
				offered a gorgeous view of the valley.
			</p>
		</li>

		<!-- <li class="article">
      <a href="/firefly">Firefly</a>
      <span class="article-info">
        Matanzas &middot; 04/05/2023 &middot; 9pm
      </span>
    </li> -->
	</ul>
</div>

<style>
	h1 {
		text-align: center;
		font-size: 2.5em;
	}

	ul {
		list-style: none;
		padding: 0;
	}

	li {
		margin-bottom: 1em;
	}

	.article {
		display: flex;
		flex-direction: column;
		align-items: start;
	}

	a:hover {
		opacity: 0.8;
	}
</style>
