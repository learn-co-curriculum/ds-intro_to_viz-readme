
# Data Visualization in Python

## Objectives 

* Identify data visualization as a necessary tool for data scientists
* Select suitable visual cues for given context
* Rank different cues based on their effectiveness.

## Background

Data visualization is considered to be a skill of very high importance  for a data scientist's career as it provides edge while analyzing data and/or presenting analysis' findings to the decision makers. Upcoming set of lessons and labs will help you understand basic data visualization principles and explain some terminology related to data visualization. We shall mainly be using python's `matplotlib` library to visualize different datasets.   

![](https://3c1703fe8d.site.internapcdn.net/newman/gfx/news/hires/2013/whatmakesada.png)

### Why Visualize?

Data visualization is an excellent way to communicate complex set of information in an easy to understand way. Human beings have an outstanding ability to recognize visual patterns and do visual comparisons. Due to this reason, using visualizations like charts or graphs to visualize large amounts of complex data is considered much more productive than working with spreadsheets or reports with loads of numercial information.

>Data visualization is a quick, easy way to convey concepts in a universal manner. 

Data scientists use visualization technqiues in order to:

* Visually identify areas that need attention or improvement.
* Clarify which factors influence the desired outcome and how much.
* Help understand and communicate ordering of data entities.
* Show predictions or other outcomes of an analysis. 

In the following section, we shall look at some of the basic principles which are used towards making meaningful visualizations. We shall later use these principles to draw our own visualizations using python. 

### 1. Data Encoding 

Data visualization mainly concerns itself with encoding the data using *"Visual Cues"*. This involves mapping the data as variations in position, size, colour, length and volume etc. Following figure depicts some visual cues that are routinely used for data visualization and follow human cognition. 

<img src="cues.png" alt="drawing" width="500"/>


Some of these visual cues work better than the others for communicating information e.g. its easier to differentiate between colors of different objects vs. lengths of  different lines. Can you quickly have a look at these cues above and try to figure out which one is easiest to evaluate by human eye? color, area, position. 

The interpretation of these cues maybe considered subjective and all cues are not considered equally revealing. In the paper titled **Graphical Perception and Methods for Analyzing Scientific Data**, researchers Cleveland and McGill came up with some ideas on how human beings precieve different visual cues with varying level of impact. Their paper on the topic is available [HERE](http://courses.ischool.berkeley.edu/i247/f05/readings/Cleveland_GraphicalPerception_Science85.pdf). In summary, a peerceptual heirarchy of visual cues based on this work can be shown as below:


<img src="cues_heirarchy.jpg" alt="drawing" width="300"/>


This hierarchy generally works quite well for continuous variable where a bar chart based on length of bars would always work better than colour intensity or hue in order to highlight the difference between different quantities. But this does not mean that one would ALWAYS use a bar chart. For nominal and ordinal variables, difference in Hue and contrast may well prove to be more effective than length. With a focus on how human brains percieve colours, lengths, patterns and shapes, a data visualisation expert would choose different encoding mechanisms to suit the need of underlying data and audience of the visualisation. 

### 3. Selecting Appropriate Visualisation

Following diagram provides a good start for identifying a suitable visualisation type for the given problem. The visual cues shown above can be used for visualizing comparisons and compositions of data elements, in a static as well as a temporal context. It also gives some indication for techniques that might be useful towards showing distributions or random variables. 

![](chart-selector.png)

Bases on this, we shall cover following visualization techniques in the upcoming series of lessons and labs:
* #### Comparisons with Bar Charts
* #### Temporal Comparisons with Line Plots and Area Charts
* #### Compositions with Pie charts and Simple/Multi-level Donut Charts
* #### Relationships with Scatter Plots
* #### Geogrpahical Plots 


## Summary

This lesson provides a very brief introduction to data visualization. We looked into how different visual cues can be used for depicting data as a graphic. We also looked at how some of the cues might be more effective than others towards visual analysis of data. The chart given in this lesson will be used to cover some of the plotting techniques in Python, Numpy and Pandas in upcoming lessons and labs. 
