# Introduction

Without good communication, designers who are unaware of solutions may be forced to ‘reinvent the wheel’, wasting unnecessary effort on a problem that has already been solved by others. Thus this section attempts to capture and codify  best practices solutions to information visualisation design problems for those engaged in the practice. This list is  a combination of curated content from notable sources in the industry such as NNgroup and Juice Analytics, and also draws on experiential learning gained from working on client projects at Axis Group.

## General Design Principles

This section attempts to highlight some general design principles that should be followed when designing data vis. These should be treated as 'heuristics' because they are broad rules of thumb and not specific usability guidelines. Another important thing to note is that not all of these can be incorporated into a single dashboard and there is usually a tradeoff involved eg. flexibility vs. minimizing choices. Instead, we suggest prioritizing one or two general principles in order to stay focused. 

### The Mantra We Follow for Seeking Visual Information

> **Overview first, zoom and filter, then details-on-demand.** 
>
> [Shneiderman, 1996]

- [Overview](http://www.infovis-wiki.net/index.php?title=Overview)
- [Zoom](http://www.infovis-wiki.net/index.php?title=Zoom) and [Filter](http://www.infovis-wiki.net/index.php?title=Filtering)
- [Details on demand](http://www.infovis-wiki.net/index.php?title=Details_on_demand) (Gradual Reveal)
- [View Relationships](http://www.infovis-wiki.net/index.php?title=View_Relationships&action=edit&redlink=1)
- [History](http://www.infovis-wiki.net/index.php?title=History&action=edit&redlink=1)
- [Extract](http://www.infovis-wiki.net/index.php?title=Extract&action=edit&redlink=1)

The Visual Information-Seeking Mantra [Shneiderman, 1996] summarizes many visual design guidelines and provides an excellent framework for desiging Information visualization applications.

### Information Discrimination

> “Data isn’t like your kids, you don’t have to pretend to love them equally.”
> Amanda Cox, NY Times

In their guide on 'Designing Dashboards People Love to Use', Juice analytics break this principle down into 3 succinct steps-

> **Find the core**. Your dashboard should be more than just a lot of data on a screen. It should have a core theme based on the essence of the problem.
>
> **Ask a better question.** Dashboard requirements can quickly turn into a laundry list of unrelated metrics, dimensions,and half-baked analyses. The root of this problem stems from only asking “what would you like to know?” Here’s the one follow-up question you need in order to narrow down the list: “What would you do if you knew this information?” 
>
> **Reporting vs. exploration.** For all the things that a dashboard can be, it cannot be a generic analysis tool. It cannot be designed to slice and dice data to explore and answer a new question every time. This is a dynamic we refer to as the difference between herding cows and herding cats.
>
> Designing Better Dashboards, Juice Analytics

To sum up, ask the following questions when making decisions-

* What metrics are a must, or necessary to all users?
* What’s necessary to certain users, but not to the others?
* What’s nice to have but not necessary?
* What doesn’t really make sense?


### Reduce Cognitive burden/ Cognition is a scarce resource

#### Attention

> "Attention is a resource —a person has only so much of it."
>
> Matthew Crawford

**Separate news from the noise**- Make important information salient and easy to get to using visual cues, interaction techniques, and other functionalities. Avoid clutter.

**Push vs. Pull**- To the extent possible, the burden of highlighting important information should be borne by the interface, and not by the user, e.g. by way of alerts and notifications.

#### Memory

Promote recognition rather than recall by using familiar metrics and common patterns. When needed, provide details so that  the user does not have to remember information from one part of the dashboard to another.

Allow people to bookmark, save, tag and annotate- so they dont have to remember what was interesting

Instructions for use of the system should be visible or easily retrievable whenever appropriate.

#### Computation

Calculate the right metric for users, and provide the most actionable metric or information. For example, it may be important to focus on variances rather than absolute changes (e.g. change in sales since last year vs. total sales).


#### Perception

Use recognizable icons and UI components with clear affordances.

Maximize contrast between data and the background to increase readability.

Group similar elements together by using white space, borders, and/or tiles.

Ensure distinguishability between elements.

Use clear affordances so that users will know how to interact with a chart, whether it's clickable or hoverable.

#### Easy Learnability

Simplicity is key!  

Layout and order of presentation matter. Start with the summary-level metrics first, and uncover more complex data and charts as user works through the dashboard. 

#### Readability

Many factors play into the readability of your content, such as typeface, font size, color, etc. The following is a font framework that Juice Analytics has provided:
* Body text is clean, readable content
* Headers separate and name major sections of your work
* Notes describe additional things the reader should be aware of. These should fade
  into the background unless we call attention to them.
* Emphasis text is what we want our reader to pay particular attention to. 

Use this framework to make decisions on typeface (serifs vs. sans serif), font size, and color. 

Additionally, to ensure comprehension the system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms

### Context matters

Paraphrase+add attribution

> People need context and explanation to understand new and unfamiliar events. Providing data without text, labels, or instruction is the difference between a chef presenting a gourmet meal and fishmonger throwing a mackerel at your head. Letting the data speak for itself can be a recipe for misinterpretation and confusion.
>

### Flexibility

Build in flexibility to allow the dashboard to become relevant for different users but also **provide good defaults**. The most common way to allow users to customize the dashboard is by defining the scope of the data using filters. Other options include designingthe dashboard to let users save the view they’ve configured or offering easy ways to tag or highlight particularlyrelevant information. 

### Current Selections/ Visibility of system status

The system should always keep users informed about what is going on, through appropriate feedback within reasonable time. Eg. Keeping users updates with current selections applied to the data so they know they are looking at a filtered dataset.

### Actionability

Enable users to not just get insights from their data and complete tasks quickly but also be able to take actions based on what the data reveals. Call out items in a dashboard like outliers, issues, alerts, changes in metrics. Take it one step further by providing guidance on what the next step is. For example, if the revenue of a company has dropped by over 50% from the prior year to date, highlight this piece of information but also have additonal visulizations to show why this has happened to enable the user to take action based on the information. 

### Compactness
> “Compactness is the property that a design can fit inside a human being's head...Compact software tools have all the virtues of physical tools that fit well in the hand. They feel pleasant to use, they don't obtrude themselves between your mind and your work, they make you more productive.
>
>  Compact is not equivalent to ‘weak’. A design can have a great deal of power and flexibility and still be compact if it is built on abstractions that are easy to think about and fit together well. Nor is compact equivalent to ‘easily learned’; some compact designs are quite difficult to understand until you have mastered an underlying conceptual model that is tricky, at which point your view of the world changes and compact *becomes* simple. ”
>[Eric Steven Raymond](http://catb.org/~esr/writings/taoup/html/ch04s02.html)

Few tactics to design compact dashboards- 

1. Break a dashboard into bite-sized pieces, each built around a key question.
2. Increase data-ink ratio by leveraging data dense visualization techniques such as small multiples, glyphs, sparklines etc.

### Minimize Choices

To the extent possible reduce the number of choices a user has to make. Less is more in design. Having a screen with multiple toggles, filters and animations can overwhelm the user if not designed right. 

### Redundancy in perceptual cues not Information

Avoid excessive redundancy in information as it can add clutter. For example, labeling the axis of a bar chart as well as directly labeling the value of the bars can be redundant.

### Content as Navigation

While the navigation bar does serve as an 'emergency exit', designers should bake in interactions into the visualization itself so that users are able to achieve different steps of their workflow using the content.



#### Others TBD:

Accessibility and Universal Design

Error Prevention (also resetting current selections to default values)

Consistency and Standards

Help users recognize, diagnose, and recover from errors

Help and Documentation

## References

https://www.mat.ucsb.edu/g.legrady/academic/courses/11w259/schneiderman.pdf

https://www.nngroup.com/articles/ten-usability-heuristics/

https://juiceanalytics.squarespace.com/s/Guide_to_Dashboard_Design.pdf

http://www.juiceanalytics.com/writing/better-know-visualization-small-multiples



## Axis Style Guide
[Axis Group Visual Style Guide for Dashboards](https://sites.google.com/view/style-guide/guidelines)

