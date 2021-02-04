# jquery-scrolly

This will make horizontally scrolling backgrounds on webpages.

## Getting Started

* link the styles and js from your page (and also have jquery)
```
    <link href="styles/scrolly.css" rel="stylesheet" />
    <script src="scripts/jquery-scrolly.js"></script>
```

* call the makeScrolly function on an element and pass in the settings that setup the scrolling background
```
$("body").makeScrolly({ id : "clouds", image : "images/clouds.png", height: 117, top: 100, speed: 1, zindex: 100 });
```

## Usage

Settings you can pass when settin gup a scrolly are:

height (default 100) - how tall the scrolling section should be in px

image (required) - the image that scrolls in the background

top (required) - where the scrolling background is displayed on the page e.g. 0 = top of the page, 200 = 200px from the top

speed (default 5) - how fast the background scrolls; bigger number is faster. Negative numbers will scroll right to left.

id (optional) - if passed will be set as the id of the created html so you can attach styles to it if you want

zindex (default 100) - the z index of the element; determines which scrolling background is 'on top'

iterationWait (default 80) - controls the timeout value/the wait between each speed change; generally ignore this, but can set it if you want more control over speed

## Examples

There is an example.html in the examples folder, which can be previewed: https://jqueryscrolly.netlify.app/examples/example1.html

![Example 1](examples/example1.gif?raw=true "Toot toot")
