# hero-with-video-bg
Videos can augment your brand and user impression; with a video background you can overlay text for a clear call-to-action.

## Tutorial
For detailed instruction's, view Solodev's [Hero with a Video Background](https://www.solodev.com/blog/web-design/bootstrap/hero-with-a-video-background.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/mjp3h5n1/2/).

## HTML
The tutorial contains the following basic HTML markup.

```
<header class="home-hero" role="banner">
				<video autoplay="" id="heroVideo" loop="" muted="" poster="https://raw.githubusercontent.com/solodev/hero-with-video-bg/master/images/hero-video-poster.jpg">
					<source src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/blob/master/videos/hero-video.mp4" type="video/mp4" />
					<source src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/blob/master/videos/hero-video.webm" type="video/webm" />
					<source src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/blob/master/videos/hero-video.ogv" type="video/ogv" />
				</video>
				<img alt="poster image mobile" class="poster img-fluid mx-auto d-block d-sm-none" src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/master/images/hero-video-poster.jpg" />
				<div class="container d-flex flex-row">
						<div class="row">
							<div class="col-lg-12 d-flex flex-column justify-content-center text-white py-md-5 text-container">
								<h2 class="display-4 mb-0">Be part of the <span class="d-block font-weight-bold">Lunar XPerience</span></h2>
								<p class="lead my-4">If you're an explorer, then the moon is calling.
									<br>Join the LunarXP mission where new worlds await.</p>	
									<a class="btn btn-outline-light w-max mt-2" href="#" tabindex="0">Tour Our Ships</a>
							</div>
						</div>
					</div>
			</header>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
 <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
 <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
```
