# Visualization Narrative
The project follows the interative slideshow narrative visualization structure. The Home represents the base of what is the visualization structure. The user is being prompted and led to the author driven content and will be led through two additional scenes representing stem. In each scene, user is welcome to explore specific data point on the graph with detailed corresponded datum, which means that users can decided to do whether they are going to drill down into details in a slide

Each scence contains regarding the Visualization section at the bottom of the page. So that the reader could read more and learn more about the how is scenes, triggers, annotations and paramters for that particular page.

# Narrative Structure
There are three scenes in the narrative visualization. They follow the same template and layout for visual consistency. The title fixed at the very top of the html page, above the visualization container for the duration of the narrative visualization. The scenes is consistent with the flow to keep the reader from getting disoriented through transitions. The order of scene is consistent with are chosed with the basis of the categorical varibale attached with automobile, which are displacement, horsepower, acceleration The visualization container which displays the data and is consistent with height 500px, width 1000px, the background is set to white ,and the fills and strike also are painted with black. The scatterplot has the consistency with the legend and axes for the duration of the narrative visualization. The data has been concluded with the axes. The annotation and each of marks's color also are have consistency during the whole narrative visualization.

# Scene
In order to find the conclusions of the survey research on the number of cylinders and the overall performance of the car, the three most critical aspects are listed for comparison, based on the correlation of car performance.Consequently they are displacement, horsepower, and acceleration. These three scenarios were investigated separately. The correlation between the number of car cylinders and each of them, from positive to negative related scene change state.

The menu items in the navigation bar of each page enables the User Interface events. User interacts by clicking on the button or menu items to navigate to various part of this story. The mouse hover is another user interface event. The hover event allows proper positioning of the tooltip. As mouse moves from one bar to another, changes in X and Y position causes opacity to revert back to its original state in the previous bar and change in the new bar.

# Annotations
The annotation is provided by the legend on the top right of the chart with fixed boxes and a tooltip when mouse is hovered over different scatterplot in the chart. Addtionally, the legend and labels along the X and Y axis provides additional annotations for the chart.

# Triggers
In the navigation bar, the mouse click acts as a trigger event. The mouse hover (mouseover) event is a trigger for the tooltip in the bar chart. The highlighted icon in the navigation bar and colored buttons,relative the whole body, with icons and the text-style words telling(Ex. Scene2, Secene3) provide the visual clues about the user actions triggers to the user.

# Parameters
Parameters are used for the users explore and get more details in the narative visualization. The types of parameters engaged in the visualization is the number of cylinders Users will have the ability to examine the data with specifi deatils for each vehicle they are looking at every time("Three Cylinder unit car", "Four Cylinder unit car", "Five Cylinder unit car", "Six Cylinder unit car", "Eight Cylinder unit car"). By doing this, users could know more details on the scatterplot which they are looking at, and then they can compare with other circle ,whiling looking the Y-axis and X-axis to get their own more details result and answer. The current state is under control of the parameter automobile "cylinders". When users mouseover to a single data point belonging to that vehicle's data, the cylinders, the current state will changes. Then the data points belonging to it will become stroke whitesmoke and opacity set to 1,from opacity 0.3 Consequently this allows user can communicate with the associated data by mouseover action.

Additional Note
Below are Online Code Reference

[Tool-tip](https://d3-graph-gallery.com/graph/interactivity_tooltip.html) User action Css control D3-Annotation Tutorial
