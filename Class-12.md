# Chart.js

- (REF: https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

## How to make charts

1. (REF: https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) Setting up: The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:

2. Drawing a line chart: To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

3. Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. Add this immediately above the line that begins ‘var buyers=’.

- Drawing a pie chart.

- Drawing a bar chart

- Conclusion

## Basic Usage (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

- At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

- Fallback content: The canvas element differs from an img tag in that, like for video, audio, or picture elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

Providing fallback content is very straightforward: just insert the alternate content inside the canvas element. Browsers that don't support canvas will ignore the container and render the fallback content inside it. Browsers that do support canvas will ignore the content inside the container, and just render the canvas normally.
 
## Domain names and hosting

- Domain names (html bk, pg 487): Your domain name is your web address. 

- Web Hosting (html bk, pg 487): So that other people can see your site, you will need to upload it to a web server. 