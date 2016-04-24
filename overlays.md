---
layout: default
---
<div id="homepage--body">
	<div class="row clearfix">
		<div class="full column">
			<p class="callout">If you have a request feel free to contact me at <a href="mailto:thyroidgland.twitch@gmail.com" target="_blank">thyroidgland.twitch@gmail.com</a>. Give me a <a href="http://www.twitch.tv/thyroidgland" target="_blank">follow on Twitch</a> if you’re so inclined to!</p>
		</div>
	</div>
	<div class="row clearfix">
		{% for overlay in site.data.overlays %}
		<div class="full column set-project">
			<h2 class="section-title">All Game Overlays</h2>
			<h2 class="set-title"><!-- <a href="{{post.url}}"> -->{{overlay.title}}<!-- </a> --></h2>
			<div class="row clearfix">
				<div class="full">
					<img class="set-preview" src="{{ overlay.img1 }}" alt="">
				</div>
			</div>
			<div>
				<a href="{{overlay.download}}"><p class="download-button">DOWNLOAD</p></a>
			</div>
		</div>
		{% endfor %}
	</div>
</div>