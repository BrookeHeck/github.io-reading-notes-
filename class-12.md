# Chart.js, Canvas

## Summary
These readings introduced the canvas tag and chart.js, which go together nicely. The canvas tag allows a developer to draw 2D graphics on the specified height and width of the canvas element. Chart.js is a tool that uses the canvas element, but is used to create charts and graphs on that canvas. I haven't used it yet, but it looks way easier than trying to create a graph on my own. From the examples it looks like you add some labels, input data, and change some properties and then you have yourself a chart. I'm excited to try this out in an actual project.

## JavaScript Canvas
1. What does the canvas allow a developer to acheive?
- Canvas allows a developer to draw 2D graphics using JS.

2. What is the importance of the closing canvas tag?
- Everything between the open and closing canvas tag will be the fallback content if the 2D drawing is not rendered or the browser doesn't support canvas.

3. Explain what the getContext() method does.
- The get context method returns a render context object. For example, if you passed '2d' into getContext(), you would get the CanvasRenderingContext2d object. Then you can change properties or call object methods on that object to draw on the canvas.

## Chart.js Documentation
1. What is Chart.js and how it can be brought into your project?
- Chart.js is a tool that helps create charts within a canvas element. It can be downloaded from npm, GitHub, or Chart.js CDN. 
2. List 3 different Chart types you can create using Chart.js.
- Area, bar, bubble, doughnut/pie charts, line, mixed, polar, radar, and scatter

## Easily Create Stunning Animated Charts with Chart.js
1. What are some advantages to displaying data via a chart over a table?
- Charts convey data quickly and are easier to look at than a table.

2. How could Chart.js aid your previously created applications visually?
- My first thought was all the tables in the salmon cookies project. I think that a bar graph would have been a much more visual representation than just numbers. Anyone could quickly and easily see the best and worst perfomring stores based on the size of the bar.

## Things I want to know more about
- I didn't dive to deep into the docs of chart.js, but it looks like a great way to create graphs and charts. I would like to read through the docs more when I have time.

### Links
[JavaScript Canvas](https://www.javascripttutorial.net/web-apis/javascript-canvas/)
\
[Chart.js Documentation](https://www.chartjs.org/docs/latest/)
\
[Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
\
[Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
\
[Applying Style and Colors - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
\
[Drawing Text - Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)