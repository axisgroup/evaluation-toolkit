# Introduction

Without good communication, designers who are unaware of solutions may be forced to ‘reinvent the wheel’, wasting unnecessary effort on a problem that has already been solved by others. Thus this section attempts to capture and codify  best practices solutions to Information Visualisation design problems for those engaged in practice.

## General Design Principles

This section attempts to highlight some general design principles that should be followed when designing data vis. These should be treated as 'heuristics' because they are broad rules of thumb and not specific usability guidelines. Another important thing to note is that not all of these can be incorporated into a single dashboard. Instead, we suggest prioritizing one or two general principles inorder to stay focused.

### Visual Information Seeking Mantra

> **Overview first, zoom and filter, then details-on-demand.** 
>
> [Shneiderman, 1996]

- [Overview](http://www.infovis-wiki.net/index.php?title=Overview)
- [Zoom](http://www.infovis-wiki.net/index.php?title=Zoom) and [Filter](http://www.infovis-wiki.net/index.php?title=Filtering)
- [Details on demand](http://www.infovis-wiki.net/index.php?title=Details_on_demand) (Gradual Reveal)
- [View Relationships](http://www.infovis-wiki.net/index.php?title=View_Relationships&action=edit&redlink=1)
- [History](http://www.infovis-wiki.net/index.php?title=History&action=edit&redlink=1)
- [Extract](http://www.infovis-wiki.net/index.php?title=Extract&action=edit&redlink=1)

The Visual Information-Seeking Mantra [Shneiderman, 1996] summarizes many visual design guidelines and provides an excellent framework for desiging [Information visualization](http://www.infovis-wiki.net/index.php?title=Information_visualization) applications.

### Information Discrimination

> “Data isn’t like your kids, you don’t have to pretend to love them equally.”
> Amanda Cox, NY Times

**Find the core**. Your dashboard should be more than a lot of data on a screen. It should have a core theme based on the essence of the problem.

**Ask a better question.** Dashboard requirements can quickly turn into a laundry list of unrelated metrics, dimensions,and half-baked analyses. The root of this problem stems from only asking “what would you like to know?” Here’s the one follow-up question you need to narrow down the list: “What would you do if you knew this information?” 

**Reporting vs. exploration.** For all the things that a dashboard can be, it cannot be a generic analysis tool. It cannotbe designed to slice and dice data to explore and answer a new question every time. This is a dynamic we refer to as the difference between herding cows and herding cats.

### Cognition is a scarce resource

#### Attention

> "*Attention* is a *resource*—a person has only so much of it."
>
> Matthew Crawford

**Separate news from the noise**- Make important information salient and  easy to get to using visual cues, interaction techniques and other functionality; Avoid clutter



**Push vs. Pull**- To the extent possible, the burden of highliting important information should be borne by the interface. Eg. by way of alerts and notifications

#### Memory

Recognition rather than recall?

Details when needed

Allow people to bookmark, save, tag and annotate- so they dont have to remember what was interesting



#### Computation

Calculate the right metric for them, provide the most actionable metric or information eg. Focus on absolute measures rather than changes (e.g. total sales vs. change in sales)

#### Perception

Recognizable icons, UI components with clear affordance

Distinguishable elements

Grouping thigngs togehter using whitepsace and or border, Using tiles

Clear affordances- people should know how to interact with a chart, is it clickable? is it hoverable?



### Context matters

People need context and explanation to understand new and unfamiliar events. Providing data without text, labels or instruction is the difference between a chef presenting a gourmet meal and fishmonger throwing a mackerel at your head. Letting the data speak for itself can be a recipe for misinterpretation and confusion.

### Flexibility

Build in flexibility to allow the dashboard to become relevant for different users but also **provide good defaults**. The most common way to allow users to customize the dashboard is by defining the scope of the data using filters. Other options include designingthe dashboard to let users save the view they’ve configured or offering easy ways to tag or highlight particularlyrelevant information. 



### Actionability

Empower the user to finish their task quickly and/or understand the action that should be taken based on theresults. You can build in explicit guidance about what a change in a metric means, or who to contact to address an issue that is highlighted in the dashboard. 

### Compactness

Some dashboards become large and unwieldy in an effort to create a single comprehensive view of an entire business or process. Eric Steven Raymond, writing about good software design
(http://catb.org/~esr/writings/taoup/html/ch04s02.html), offers this guidance:
“Compactness is the property that a design can fit inside a human being's head...Compact software tools have all the virtues of physical tools that fit well in the hand. They feel pleasant to use, they don't obtrude themselves between your mind and your work, they make you more productive.”
A dashboard can be broken into bite-sized pieces, each built around a key question



## References

https://static1.squarespace.com/static/52f42657e4b0b3416ff6b831/t/55b9117ae4b060a0d84fef15/1438191994754/Dashboards_People_Love_To_Use_Whitepaper_v2.pdf

https://www.mat.ucsb.edu/g.legrady/academic/courses/11w259/schneiderman.pdf






## Axis Style Guide

