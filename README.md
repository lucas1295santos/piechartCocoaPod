# piechartCocoaPod
## A Swift Cocoa Pod to display pie charts with no sweat! :)

Using this Pod is preaty simple: install it like you would install any other pod, there is no other dependency needed.

To create a Pie chart use an UIVIew, and use the class PieChartView on it (picture bellow)


To populate this pie chart with your data, do as the following:

1 - Create an Array of PieChartData, informing for each object the name, the desired color and the percentage of that value on the total. There is no limt on quantity, just be sure that the total percentage is not greater than 100, or your drawing will not be accurate.

2 - Get a reference for your PieChartView

3 - Pass your array to this reference's (name) variable

And that is it!
Update this value any time you want for a new drawing.

I'm still working on this project to display more to this data, like a subtitle explaining the colors and such.
