# Titanic-Data-Viz
A data visualization exercise using titanic passenger survival dataset.

Summary -
in no more than 4 sentences,
briefly introduce your data visualization and
add any context that can help readers understand it

Design -

Graphic:
I chose the bar chart because it is the best tool to compare between
two categories. From the data, I saw that gender and cabin class are the factors
which affect the survival rate. Other factors such as age and presence of
family did not seem as influential. Grouping by gender and subgrouping by cabin
class was chosen because the arrangement gave a clear trend line for survival rate.
Showing survival count as a stacked bar graph allows the comparison between overall
count and survived count in each category.

I also wanted to limit the number of
factors displayed in the chart for the sake of clarity. Even when controls were
being operated on, the chart does not change much, avoiding any confusion to the
viewer.

One of the feedbacks I got about the chart layout was that when there is only one
bar displayed, I could unstack the bar or use a different style of visualization.
I decided to unstack the graphics, but decided against changing the visualization
too much (using a different style) to avoid confusion and instead
added a label to draw the viewers eyes directly to one specific bar for survival rate.

Color:
My first choice for color was deep red and green. This seemed a natural choice because
the graphic was trying to convey one category as "dead" (danger!bad!) and the other
as "survived" (pleasant!good!). Red and green have this meaning associated with
them because of their use in various situations like traffic lights and stop signs.
A concern I had was that red and green shades together in a graph are not
suitable for general audience because people with color blindness will not be
able to distinguish the shades. The association of "good/bad" with "green/red"
was too strong in this particular visualization, so I decided to treat this graph
as an exception to the rule.

One of the feedback I got was that colors were too bright, and muted colors may be better.
I chose to mute the colors by choosing pastel shades of red and green.

Controls/Navigation:

I visited a number of visualizations on Titanic data set created by Udacity students
for their final projects. I chose to adopt things that I liked from some of these
visualizations. I also wanted to present a different approach, chose to ask
the reader a specific question and give the user controls that enabled them
to answer that question. This came from what I asked myself during exploration
of this dataset in the Intro to data science course. From the feedbacks I received,
I am glad that the audience liked this approach and thought it to be effective.

I chose two visible controls - gender and cabin class, which changed the format
of visualization (multiple groups changed to single group, stacked bar became
unstacked). I also chose two controls, age and presence of family that
filtered the data, but did not change how the graphic was drawn. This was to
provide additional motivation for the audience to play with the graphic and also
because these factors were readily available in the dataset. 



Feedback -

Feedback1:

I like how you engaged the reader with the title and with the choice.
It invites the readers to explore the visualization.

You solve a problem or showing number versus percentage with two graph,
which is good. ( I struggle myself on which one to choose)

The colors dead/ survived are very strong, you can use more subdued colors,
and add the class as a sub-category within the gender category.

Hope that help
Emmanuelle

Feedback2:
Great job! I think the idea of putting the reader in the shoes of a person
on board the Titanic is very powerful - it immediately piques people's
interests to explore and play with the visualization.

For visual part, maybe there's no need for the background grid lines?
Also, when there's only one bar to show, it appears that the comparison
between different groups is not strong and clear enough.
So maybe you can split the stacked bars to form two separate bars
or even consider other forms of visualization?
Just some ideas for your consideration.

Keep up the great work!

Feedback3:
What do you notice in the visualization?
  The bar chart is explanatory
  On selecting a region, loved the animated line which gives me y-axis value
  Hovering on a region gives me the data
  The toggle between count and percentage does not have a label/explanation.
What questions do you have about the data?
  What is the chance of someone like me surviving...
What relationships do you notice?
  Female had a higher chance of survival (in first & second class)
  Male, especially in 2nd and 3rd class didn't have a chance of survival.
What do you think is the main takeaway from this visualization?
  Having one screen to answer all the questions.
  The user can filter the charts based on different data points.
Is there something you don’t understand in the graphic?
  No.

Resources:
colorpicker.org
