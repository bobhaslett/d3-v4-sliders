# sliderFactory

Pre-styled SVG sliders created using version 4 of Mike Bostock's d3 library. Each slider needs a div to act as a placeholde to be called into. An SVG element is appended to the div and contains all the slider geometry.


### Prerequisites
You will need the [d3 library](https://d3js.org/) installed

## Installing
### Manually install

Download the repository. Move the sliders.js and styles.css into your project folder. To link the slider function and styles to your project insert the following code into your index.html header.
```
<script src="slider.js"></script>
<link rel="stylesheet" type="text/css" href="./sliders.css">
```

### NPM install
This is not yet available

at the x=margin.left, y=zero plus the top margin. The default SVG height is set to 55px and margin.top is set at 20px, enough room for the handle and a scale underneath. When adding labels (Slider 4) you should adjust the height and margin.top.

![alt tag](https://bobhaslett.github.io/d3-v4-sliders/images/slider.png)

Vertical sliders are appended at x=width/2+left.margin. This makes them easier to control when they are made responsive. They also need a larger top.margin when a label is added

The handle moves by increments of one interger as a default but again this can be set easily with the .step() parameter (Slider 3).

## Getting Started
To see working examples and the sample code please [view here](
https://bobhaslett.github.io/d3-v4-sliders/index.html)
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
