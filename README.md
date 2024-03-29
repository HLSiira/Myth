<div align="center">
    <h1><a href="https://github.com/hlsiira/myth">Myth</a> - A mesmerizing pulsing hexagonal background.</h1>
</div>

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

</div>

## Installation

Add myth.min.js to your websites sources and the CSS to your site. It will run on document load, and either create it's own canvas element, or use one you've predefined.

```html
	<canvas id="myth"></canvas>

	<script src="myth.min.js"></script>
```

```css
#myth {
	left: -20px;
	/*opacity: .15;*/
	position: fixed;
	top: -20px;
	z-index: -1;
	pointer-events: none;
	height: 120vh;
	width: 120vw;
	background: linear-gradient(-45deg, #000 40%, #0074D7 50%, #000 60%);
	background-size: 600% 600%;
	animation: gradient 10s linear infinite;
}
@keyframes gradient {
	0% {
		background-position: 0% 51%
	}
	50% {
		background-position: 100% 50%
	}
	100% {
		background-position: 0% 51%
	}
}
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Source
Created from [Hexagons.js by ZackTheHuman](https://gist.github.com/zackthehuman/1867663)
