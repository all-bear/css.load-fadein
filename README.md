# Load Fade In

Css lib which allows you to control appearing of components after page load.

## How it works

First of all you need to include css file to your project
```css
<link rel="stylesheet" type="text/css" href="/dist/load-fadein.css"/>
```
Then you will be able to control appear order of elements with this css classes:

- _fadein-on-load_ - you need to add this class to all elements which will be controled
- _fadein-to-{{n}}_ - this class controls end value of opacity for element, you need to change _{{n}}_ to value from 0 to 10, 0 - means end value 1 for opacity, 10 means end value 1 for opacity
- _fadein-by-{{n}}s_ - this class controls speed of apearing element, _{{n}} - is a time of apearing from 1 to 50
- _fadein-delay-by-{{n}}s_ - this class controls delay before start of apearing element, _{{n}} - is a time of delay from 1 to 50
 
## TODO

- Add timing function
- Add demo
- Add bower
