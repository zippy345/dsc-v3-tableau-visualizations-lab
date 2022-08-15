
# Useful Visualizations - Lab

## Introduction
In the previous lesson we discussed a few of the visualizations that are very useful in Tableau. In this lab, we will generate each of the vizzes we discussed and add a little extra useful information. We will then save the vizzes to Tableau Public for use in a later lesson.

## Objectives
You will be able to: 
* Generate a useful Bar Chart
* Create an informative Scatter Plot
* Generate a Line Graph with a Trend Line
* Save all vizzes to Tableau Public

## Getting Started
Open Tableau Public and load the __SuperStore_ data set. Choose the _Sales_ worksheet and drag it to the workspace. Once you have done these steps, you are ready to move on to the next section.

## Bar Chart
Our first viz to create is going to be a _Bar Chart_. Drag the necessary _Measures_ to the workspace to create a Bar Chart which shows the _Profit_ by _Sub-Category_. 
* Make the viz fit _The Entire View_.
* Sort the values in either _Ascending_ or _Descending_ order, whichever you prefer.
* Add some _Color_ to show the different _Category_ each item is in. You can keep the default color palette or you can choose your own colors.
* Add a _Label_ to the _Profit_ to show the value for each of the _Sub-Category_ elements.
* Format the _Label_ to show that it is currency and make it easier to read by scaling the values to thousands with _0_ decimal places.
* Change the information for the _Category_ in the _Tooltip_ so it reads "Department" instead of "Category."
* Add a custom _Title_ and make it something descriptive like "Profits by Sub-Category."

Now you have a Bar Chart that has some useful information on it. You can see that all of the bars are colored in one of three colors which shows which _Category_ they are in. You can easily see values of each bar in the chart with the _Label_ at the end of each bar. You can hover over any of the bars and see the information in the _Tooltip_ and the _Category_ is now labeled as _Department_. 

> __Level Up__
> * Add some additional details like _Bold_ text to the _Department_ in the _Tooltip_. 
> * _Italicize_ the currency amount in the _Tooltip_.
> * Edit the _Profit_ Axis and add a dollar sign to the values to reflect that it is currency.
> * Add some other color or formatting features to personalize your viz.

Once you are finished, remember to save your viz to Tableau Public so we can use it later. Once you are finished, your viz should look similar to the one below.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/useful_bar_chart.png" alt="Tableau Data Connect Menu" height=350>

## Scatter Plot
Next we will be creating a _Scatter Plot_ which will allow us to visualize the relationship between _Sales_ and _Profit_. To begin this viz, open a new worksheet and add _Sales_ and _Profit_ to the workspace. This will produce a seemingly useless _Scatter Plot_ with one shape on the viz.
* Make the viz fit _The Entire View_.
* Add detail to the viz with the _City_ measure.
* Color _Profit_ with a _Red-Green Diverging_ palette and make sure the center is at _0_ and the whole color range is used.
* Size the elements in the viz by _Quantity_ and adjust the size to make it easy to differentiate between the smaller items.
* Add a _Linear Trend Line_ to show the trend of _Sales_ to _Profit_.
* Add a meaningful _Title_ to the viz and make it eye appealing.

> __Level Up__
> * Add some color to the _Trend Line_
> * Change the _Axis_ labels to show currency in __Thousands__ with __0__ decimal places.
> * Change the shapes to show the different _Categories_ and customize the _Shape_ for each _Category_
> * Customize the _Title_ with some color.

Once you have followed these steps, you will have a viz that looks like the one below. Make sure you save your work so we can use it later.

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/sales_to_profit.png" alt="Example of the final scatter plot" height=350>

## Line Graph
Finally we would like to show the _Profit_ over time, and to do this we will be making a _Line Graph_. Begin this in the same manner as the others and add _Order Date_ and _Profit_ to the workspace.
* Change the level of the _Order Date_ to _Quarter_.
* _Color_ the _Profit_ to be __Green__ when the _Profit_ is positive and __Red__ when it is negative.
* Add quarter labels to the _Order Date_ and _Format_ it so it has only the __Quarter__ and the __Year__.
* Add a _Title_ and save your work for use later.

> __Level Up__
> * Rename the _Axis Label_ of _Quarter of Order Date_ to _Order Date:_ and add a _Subtitle_ which reads _Quarterly_
> * Add the dollar sign to the _Profit_ _Axis_ and add _Minor Tick Marks_ at __$1,000__ intervals. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/quarterly_profit.png" alt="Example of the final line graph" height=350>


## Summary
Summary goes here
