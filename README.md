# Material Chrome Themes
I noticed the lack of really good Material Chrome Themes available in the Chrome Web Store, so I decided to create a few of my own. They're really simple and visually appealing, and are meant for the early-2019 redesign of Chrome.

## Installation
If you want to use these themes, you'll have to go to [chrome://extensions](chrome://extensions), enable Developer Mode, and click "Load Unpacked" to load an unpacked extension. Select the folder corresponding to the theme you want to use, and hit "Select".

I might release these to the public in the future, but it requires a $5 payment to Google. If you'd like to see these on the Chrome Web Store, [I accept donations](https://paypal.me/JamsheedMistri)!

## Screenshots
### Material Red
![Material Red theme screenshot](https://i.imgur.com/yQK31l9.jpg)

### Material Gold
![Material Gold theme screenshot](https://i.imgur.com/yBDltJg.jpg)

## Template
Here's a starter template for new themes and what each key/value pair is.
```javascript
{
	"manifest_version": 2,
	"version": "1.0", // Version of theme
	"name": "Example Theme", // Name of theme
	"theme": {
		"colors" : {
			"frame" : [R, G, B], // Behind the tabs color
			"frame_inactive" : [R, G, B], // Behind the tabs color when not focused
			"frame_incognito": [R, G, B], // Behind the tabs color in in incognito
			"frame_incognito_inactive": [R, G, B], // Behind the tabs color in in incognito when not focused
			"tab_text": [R, G, B], // Tab text color
			"tab_background_text": [R, G, B], // Unfocused tab text color
			"toolbar" : [R, G, B], // Tab background and below color
			"bookmark_text": [R, G, B], // Book mark text color
			"ntp_background": [R, G, B], // New tab background color
			"ntp_text" : [R, G, B], // New tab text color
			"ntp_link" : [R, G, B], // New tab link color
			"ntp_link_underline" : [R, G, B] // New tab underline color
		},
		"tints" : {
			"buttons" : [R / 255, G / 255, B / 255] // Tint color of control buttons (home, refresh, etc) from 0-1, where 0 is black and 1 is white
		}
	}
}
```