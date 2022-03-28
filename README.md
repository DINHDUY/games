# Games PWA
## Collection of scratch games

### TO DO

1. Create all favicon images using [RealFaviconGenerator](https://realfavicongenerator.net) and replace existing images with generated images.

	If you're able to install the CLI version of **RealFaviconGenerator**, `favicon_config.json` contains all settings to generate these images using the following command from the project's root directory. The `real-favicon` tool generates images from `favicon.png`, so replace `favicon.png` prior to running this command. The resulting `favicon_data.json` and `site.webmanifest` can be discarded:
	
	`real-favicon generate favicon_config.json favicon_data.json .`

2. Create new 650x650 maskable icon using [Maskable.app](https://maskable.app) and replace `maskable_icon.png`.
3. Create new black vector icon using [`Manytools' colorize images tool`](http://manytools.org/image/colorize-filter) and replace [`safari-pinned-tab.svg`](https://github.com/nikkifurls/simple-pwa/blob/master/safari-pinned-tab.svg).
4. Create new 1200x630 share image and replace `share.jpg`.
5. Build your PWA by adding HTML, CSS, and Javascript.
