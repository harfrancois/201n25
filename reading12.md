# Creating charts with charts.js

code examples from https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/

## Setting up html with script source.
example:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>

## Drawing a line chart.
Add element to html to retrieve context.
example:
<canvas id="buyers" width="600" height="400"></canvas>

<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>

Enter chart data.
var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}

## Drawing a pie chart.
example:
Create html element.
<canvas id="countries" width="600" height="400"></canvas>

Chart data and values
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);

var pieData = [
	{
		value: 20,
		color:"#878BB6"
	},
	{
		value : 40,
		color : "#4ACAB4"
	},
	{
		value : 10,
		color : "#FF8153"
	},
	{
		value : 30,
		color : "#FFEA88"
	}
];

Add the options after the pie data.
var pieOptions = {
	segmentShowStroke : false,
	animateScale : true
}

## Drawing a bar chart.
example:
Create html element.
<canvas id="income" width="600" height="400"></canvas>

chart data and values.
var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);

var barData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "#48A497",
			strokeColor : "#48A4D1",
			data : [456,479,324,569,702,600]
		},
		{
			fillColor : "rgba(73,188,170,0.4)",
			strokeColor : "rgba(72,174,209,0.4)",
			data : [364,504,605,400,345,320]
		}

	]
}

## Canvas
The canvas element can be used to draw customized images and also apply color to them. 

Here is a list of ways to use canvas from MDN Web Doc.

The basic usage of canvas and how to apply it to your html with example.
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage

Tutorial for drawing a verity of shapes using canvas with example.
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes

Tutorial on styling and coloring using canvas with examples.
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors

Tutorial on creating/drawing text using canvas with example.
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text

I am just blown away by the verity of usage and customization you can do with canvas. Its an amazing tool.