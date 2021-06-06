# Stunning charts

**What**

_Data visualization for better display of data it can be added to java script code but it needed to setup and download charts.js and there are many types of charts : line,Pie and bar charts_ 

**why**

_as said better way for displaying data instead of table_
> have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

**how**

_by get element by id you can add achart and to create a chart you can use html or JS by declaring global id for chart then initalize a chart as object by adding new keyword then chose its type whether bar or pie then feel free to style it_
>let ctx = document.getElementById('chartone').getContext('2d');
let chartone = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'], 
        **this block of code to create a chart of type bar**

 # Shapes 
_draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes to add to your webpage and by draw function and the get element by id and makeing the height , width and calculation of shapes , they can be added_       