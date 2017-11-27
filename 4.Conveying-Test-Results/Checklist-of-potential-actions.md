

## Checklist of potential actions
This is a list of potential changes that can be made to the design based on results from the usablity test. Identify which categories below most closely matches with the users needs.

### Content/ Functional Patterns

- **Data**: show me a different metric  

- **Comparison**: show me a reference point

- **Trend**: show me how things have changed over time  

- **Outliers**: show me data points that do not fit the norm  
 Outliers identify problem areas or data points that are doing unusually well.

- **Distribution**: show data values are spread across a scale.  
Distribution is used to show the shape of data -  composition of data values that makes that up the totals. Knowing the total numbers isn't enough in this case. 

- **Location**: show me how things relate spatially  
 This shows more than just numbers. A visual representation of how things are mapped can provide insights.  

- **Part-to-whole relationship**: show the set of values that contribute to a whole  

- **Proportions**:  show relative contributions of several values to a whole  

- **Patterns/Relationships**: show correlations and associations among values  
  This reveals relationship between dimmensions/measures and how they affect each other.   

[TDWI]:(https://tdwi.org/Articles/2015/01/20/Language-of-Data-Visualization.aspx?Page=3
[Data Viz Catalog]:(http://www.datavizcatalogue.com/)

### Data Presentation

- breakout by right dimensions  

- **Indexing**  
Index values to a common point.  
Use this when the values have huge variations making it hard to view and compare points.   
Use indexing to compare how values have changed. Indexing provides a common benchmark making it easier to track change.

- **Scale**  
Start the scale from the minimum value in the dataset instead of zero.  
Use this techinique when data points are hard to see because of a large variation in values. (Note that starting the scale from the minimum value will not work for all types of charts. A bar chart must always have a zero baseline. Dot plots and line charts are examples of charts that could start from a non zero baseline.)

- **% vs. absolute values**  
Display the variance by converting absolute values to % change.  
Use % if the user cares more about tracking change or growth rather than the actual values.  

- **Averages**  
Use mean as a measure of central tendency when the data set is uniform. A data set with extreme outliers will skew the mean. A median is a more accurate representation of the central tendency in this case. If there is a large difference between the median and mean then the distribution is probably skewed. Median should be used over mean in this case. Mean is best used for normal distributions. Mode can be used to measure the most common category. The problem with mode is that the most commonly occurring item might not be a good representation of the central tendency.  

- **Quartiles**  
Mark quartiles in your chart through bands of shaded color or lines.
Use quartiles when the user wants additional context while viewing a disitribution. The lowest quartile will show where the lowest 25% of the values lie.   


### Interaction Patterns


- **Filter: show me something conditionally**

  Add or remove filtering capability  
  Use fiters if the user is overwhelmed by too much information and wants to focus on one group at a time.   
  Filter can also be used for power users who want to be able to slice and dice the data is different ways.


- **Brushing: show me connected items**

  Add or remove brushing capability  
 Use brushing when multiple visuizations on the screen have atleast one set of dimmensions that are the same. Brushing is useful when the user does not read charts in isolation and wants to view how a data point is doing across multiple visualizations.

- **Reconfigure: show me a different arrangement**

E.g. changing the sort criteria on a list    
Reconfiguring can be used when the user does not have a fixed way of viewing information.   


- **Encode: show me a different representation**

  Change the chart type altogether    
 Encoding is helpful when the user wants different insights from the same data points.


- **Abstract/Elaborate: show me more or less detail**  
  Add or remove tooltips on hover.   
  This can be used when the user wants additional context/details for only one set of information at a time. 


- **Select: mark something as interesting**  
  Highlight points on the screen, add bookmarks
  Selections are used to highlight interesting elements on the screen and view them at a later timeor share them with someone else.

- **Explore: show me something else**  

- **Alternative choices: show me alternative metrics/ dimensions**  
  Add toggles for a visulization to switch out metrics
  Alternative choices are a great way to go back forth between two or more sets of metrics visualized the same way. 


- **Starring/tagging: show me things that I may have flagged**

- **Annotate: show me my comments on a particular chart or page**

-  **Text-based summary:  show me an automatically generated textual description of the key information in the dashboard**

  ​
[Info Vis Wiki]: (http://www.infovis-wiki.net/index.php?title=Visualization_Design_Patterns)

### Accessibility

Increase text size

Increase contrast between elements

Change colors to be more distinguishable



### Language/ Vocabulary

**Meaningful Labels**

Labels that describe what data is being displayed with enough business context

Is the chart's purpose clear from its title and subtitle?


**Legends**

**Additional information:** show me additional contextual information e.g.  to learn more about how a metric is calculated/ how to read a chart

**Visual cues**

- Placement: Where we locate things on a graph with attention to both position and proximity

- Redundancy

  ​

### Aesthetics

Follow visual design principles to improve the overall aesthetics of your dashboard.
https://www.oreilly.com/learning/visual-design-principles

**Presentations on Visual Design Principles**
https://docs.google.com/presentation/d/182I3zWRQwAWXlLtB-DbfgeSrmC4XvVCpxz8sXzj7t-s/edit?usp=sharing
https://docs.google.com/presentation/d/1slIHDPWSrEJEh-OikjZPDzuePkq8v7cd9Tfhq64wiqI/edit?usp=sharing


### Structural Patterns

Flow
Hierarchy
Gradual Reveal

References:
http://classes.engr.oregonstate.edu/eecs/spring2015/cs419-001/Slides/tufteDesign.pdf
https://statistics.laerd.com/statistical-guides/measures-central-tendency-mean-mode-median.php
https://www.perceptualedge.com/articles/visual_business_intelligence/introducing_bandlines.pdf
