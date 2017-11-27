

## Checklist of potential actions
This is a list of potential changes that can be made to the design based on results from the usablity test. Identify which categories below most closely matches with the users needs.

### Content/ Functional Patterns

- **Data**: show me a different metric  
  Scenario: The user finds other metrics which are not displayed on the dashboard to be more useful. 

- **Comparison**: show me a reference point


- **Trend**: show me how things have changed over time  
  Scenario: The user wants to know how data points have been trending  


- **Outliers**: show me data points that do not fit the norm  
  Scenario: The user wants to identify problem areas or data points that are doing unusually well.

- **Distribution**: show data values are spread across a scale.  
  Scenario: The user not just wants to know totals and averages but also the composition of data values that makes that up. 

- **Location**: show me how things relate spatially  
  Scenario: The user wants to not just see numbers but a visual representation of how things are mapped. 

- **Part-to-whole relationship**: show the set of values that contribute to a whole  
  Scenario: The user wants to see the totals and also a breakdown of values that contribute to that. 

- **Proportions**:  show relative contributions of several values to a whole  

- **Patterns/Relationships**: show correlations and associations among values  
  The user needs to know if there is a relationship between dimmensions/measures and how they affect each other.   

[TDWI]:(https://tdwi.org/Articles/2015/01/20/Language-of-Data-Visualization.aspx?Page=3
[Data Viz Catalog]:(http://www.datavizcatalogue.com/)

### Data Presentation
The user finds it hard to read the charts. 

- breakout by right dimensions  

- **Indexing**  
Index values to a common point
Scenario - The values have huge variations making it hard to view and compare points.   
The user wants to compare how values have changed. Indexing provides a common benchmark making it easier to track change.

- **Scale**  
Start the scale from the minimum value in the dataset instead of zero
Scenario - Data points are hard to see because of a large variation in values. (Note that starting the scale from the minimum value will not work for all types of charts. A bar chart must always have a zero baseline. Dot plots and line charts are examples of charts that could start from a non zero baseline.)

- **% vs. absolute values**  
Scenario - The user cares more about tracking change or growth rather than the actual values.  

### Interaction Patterns


- **Filter: show me something conditionally**

  Add or remove filtering capability  
  Scenarios: The user is overwhelmed by too much information and wants to focus on one group at a time.   
  A power user wants to be able to slice and dice the data is different ways.


- **Brushing: show me connected items**

  Add or remove brushing capability  
  Scenario: Multiple visuizations on the screen have atleast one set of dimmensions that are the same. The user does not read charts in isolation and wants to view how a data point is doing across multiple visualizations.

- **Reconfigure: show me a different arrangement**

E.g. changing the sort criteria on a list    
Scenario: The user does not have a fixed way of viewing information.   


- **Encode: show me a different representation**

  Change the chart type altogether    
  Scenraio: The user wants different insights from the same data points.


- **Abstract/Elaborate: show me more or less detail**  
  Add or remove tooltips on hover.   
  Scenario: The user wants additional context/details for only one set of information at a time. 


- **Select: mark something as interesting**  
  Highlight points on the screen, add bookmarks
  Scenario: The user wants to highlight interesting elements on the screen and view them at a later timeor share them with someone else.

- **Explore: show me something else**  

- **Alternative choices: show me alternative metrics/ dimensions**  
  Add toggles for a visulization to switch out metrics
  Scenario: The user wants to go back forth between two or more sets of metrics visualized the same way. 


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

Limit clutter

Limit choices

Demphasize meta data?

### Structural Patterns

Flow
Hierarchy
Gradual Reveal

References:
http://classes.engr.oregonstate.edu/eecs/spring2015/cs419-001/Slides/tufteDesign.pdf
