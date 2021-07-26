# Data Journalism with D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

With the information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System. We tend to analyze the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand our findings.

The data set included is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/). The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."



### D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

A scatter plot is created between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

* State abbreviations are included in the circles.

* Axes and labels are created and situated to the left and bottom of the chart.

### Make interactive graphic with D3 

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

More demographics and more risk factors are included. Additional labels were placed in the scatter plot and click events were given so that users can decide which data to display. Animate the transitions for the circles' locations as well as the range of the axes. 

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how to implement tooltips with d3-tip.
