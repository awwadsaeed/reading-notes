# Canvas HTML
## brief introduction  
the canvas tag syntax is very simple it contains the opening tag `<cnavas>` and the closing tag `</canvas>` it has 2 attroputes width and height and are optional. we use the canvas tag to give us the ability to draw chart.  
## chart  
you can drow chart using the canvas tag in js. you use  `getElementById()` method to get the canvas tag and store it in a variable.  
then you create a new chart object `new chart(the canvas variable).type of chart(parameters)`.  

## chart types  
you can do a lot with the canvas tag but here are the main charts you can make:
- line chart: `new chart(canvasVar).Line(chartName)` 
- pie chart:`new chart(canvasVar).pie(pieData,pieOptions)`
- bar chart:`new chart(canvasVar).Bar(barData)`