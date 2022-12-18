<template>
	<div class="row">
		<div class="col-sm-12">
			<h1>About AI Wound</h1>
			<p>
				asdhflajhsdf askdjhf askdjf asdkfas faskdfasd faskdfhasd
				faksdfha sdfkasdhfa sdfkasjhdf askdjhf askdfasdfasdfa
			</p>
			<p>
				asdhflajhsdf askdjhf askdjf asdkfas faskdfasd faskdfhasd
				faksdfha sdfkasdhfa sdfkasjhdf askdjhf askdfasdfasdfa
			</p>
			<p>
				asdhflajhsdf askdjhf askdjf asdkfas faskdfasd faskdfhasd
				faksdfha sdfkasdhfa sdfkasjhdf askdjhf askdfasdfasdfa
			</p>
		</div>
	</div>

	<div class="row">
		<div class="col-sm-12">
			<h1>Intro Video</h1>
			<div class="video-container">
				<iframe
					width="560"
					height="315"
					src="https://www.youtube.com/embed/lj5GXZaE7qs"
					title="YouTube video player"
					frameborder="0"
					allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
					allowfullscreen
				></iframe>
			</div>
		</div>
	</div>
</template>

<style scoped>
.video-container {
	position: relative;
	padding-bottom: 56.25%; /* 16:9 */
	height: 0;
}
.video-container iframe {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
}

/* h1 {
	font-weight: 500;
	font-size: 2.6rem;
	top: -10px;
}

h3 {
	font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
	text-align: center;
} */

@media (min-width: 1024px) {
	/* .greetings h1,
	.greetings h3 {
		text-align: left;
	} */
}
</style>
