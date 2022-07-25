<script context="module">
	import { browser, dev } from '$app/env';
	import data from '../data/page.json';
	export const hydrate = dev;
	export const router = browser;
	export const prerender = true;
</script>

<svelte:head>
			 <title>{data.title}</title> 
<meta content={data.title} property='og:title'/>
<meta content={data.title} name='facebook:title'/>
<meta content={data.title} name='twitter:title'/>
<meta content={data.title} name='keywords'/>
<meta content={data.title} property='og:site_name'/>
<meta content={data.desc} name="description"/>
<meta content={data.desc} name='twitter:description'/>
<meta content={data.desc} name='facebook:description'/>
<meta content='summary_large_image' name='twitter:card'/>
<meta content='https://twitter.com/hockeycomp' property='twitter:author'/>
<meta content='https://www.facebook.com/mesinkasircomplete' property='facebook:author'/>
<meta content='https://www.youtube.com/c/bakoelraksupermarketMesinKasir' property='youtube:chanel'/>
<meta content='@hockeycomp' name='twitter:site'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='facebook:image'/>
<meta content='https://github.githubassets.com/favicons/favicon.svg' name='twitter:image'/>
<link rel="icon" type="image/x-icon" href="https://github.githubassets.com/favicons/favicon.svg" />
<meta content='Mesin Kasir' property='og:author'/>
<meta content='website' property='og:type'/>
<meta content='index, follow' name='robots'/>
</svelte:head>

<div class="content">
	<h1>{data.title}</h1>
	<h2><a href="/demo">{data.content}</a></h2>
	<h3 id={data.poss}>{data.pos}</h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.posvideo}" title={data.pos} allowfullscreen></iframe>
</div>
	<h3 id={data.android}><a href="/demo">{data.android}</a></h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.androidvideo}" title={data.android} allowfullscreen></iframe>
</div>
	<h3 id={data.register}><a href="/demo">{data.register}</a></h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.registervideo}" title={data.register} allowfullscreen></iframe>
</div>
	<h3 id={data.retail}><a href="/demo">{data.retail}</a></h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.retailvideo}" title={data.retail} allowfullscreen></iframe>
</div>
	<h3 id={data.resto}><a href="/demo">{data.resto}</a></h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.restovideo}" title={data.resto} allowfullscreen></iframe>
</div>
	<h3 id={data.bonus}><a href="/demo">{data.bonus}</a></h3>
	<div class="ratio ratio-16x9">
  <iframe src="https://www.youtube.com/embed/{data.bonusvideo}" title={data.bonus} allowfullscreen></iframe>
</div>
</div>
