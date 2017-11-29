# Planning your Test

Usability testing can uncover *all kinds* of feedback. As such, the foremost step in planning our test is picking a direction for the test. The previous sections help us frame questions about what we want to get out of the test but there is still the lingering question—how do you actually execute the test?

A quick search on Usability.gov reveals more than just a few methods to garner feedback from users from—baseline [usability testing](https://www.usability.gov/how-to-and-tools/methods/usability-testing.html) on an existing product/service to [first click testing](https://www.usability.gov/how-to-and-tools/methods/first-click-testing.html) to make sure our users go down the right path to satisfaction [surveys](https://www.usability.gov/how-to-and-tools/methods/online-surveys.html) to see how our product/service  fares in the real world.

And while at first this choice can seem overwhelming, it is important to realize that real-life constraints such as our research questions or our users' availability can help us narrow down the choices. In the next section we will attempt to break down the various steps involved when planning a usability test and provide some guidelines for each.

## Recruiting users/evaluators for your test

> After all the work with personas, by now you should have a clear idea of your target users. It also helps to segment your users based on behavior. In fact, you shouldn’t obsess over demographics. The biggest differentiator will likely be whether users have prior experience or are knowledgeable about their domain or industry — not gender, age, or geography.
Knowing who to recruit is just the first step. The more involved part is finding and recruiting them. Jeff Sauro outlines the 7 best ways to [locate the ideal users](https://measuringu.com/finding-users/) for your testing.

Source: http://www.webdesignerdepot.com/2015/02/how-to-test-the-usability-of-prototypes-like-a-pro/

Here is another excellent resource by Charline Poirier, writing for Ubuntu Design, that goes in depth  about [recruiting participants for your usability test](https://design.canonical.com/2012/03/about-usability-testing-recruiting/)

## Choosing the right test

### Overview of UX Research Landscape

This section explores the wide array of research methods available to researchers based on Christian Rohrer's—Chief Design Officer in the Consumer Division at McAfee,Inc.—excellent article [When to Use Which User-Experience Research Methods](When to Use Which User-Experience Research Methods) for NNGroup.

It then attempts to make some decisions about which methods are recommended given the Axis Design context.

The following **3-dimensional framework** with the following axes helps us simplify the task of selecting a research method- 

- Attitudinal vs. Behavioral
- Qualitative vs. Quantitative
- Context of Use

#### Attitudinal vs. Behavioral

According to Rohrer's article "this distinction can be summed up by contrasting **"what people say"** versus **"what people do"** (very often the two are quite different). The purpose of attitudinal research is usually to understand or measure people's stated beliefs, which is why attitudinal research is used heavily in marketing departments."

#### Quantitative vs. Qualitative

Both quantitative and qualitative methods are valid for evaluating visualizations. You can choose to just go with one method or use a combination of both depending what you are trying to measure. Rohrer captures the essence of these two methods when he says—

"The distinction here is an important one, and goes well beyond the narrow view of qualitative as “open ended” as in an open-ended survey question.  Rather, studies that are qucalitative in nature generate data about behaviors or attitudes based on observing them *directly*, whereas in quantitative studies, the data about the behavior or attitudes in question are gathered *indirectly*, through a measurement or an instrument such as a survey or an [analytics tool](https://www.nngroup.com/articles/analytics-user-experience/)." 

He then continues to explain what these methods are suited for—

"Due to the [nature of their differences](http://www.nngroup.com/articles/risks-of-quantitative-studies/), **qualitative** methods are much better suited for answering questions about **why or how to fix a problem** whereas **quantitative** methods do a much better job answering **how many and how much types of questions.**"



This graphic from the NNGroup website succinctly sums up the landscape thus far—![User Research Methods Landscape](https://s3.amazonaws.com/media.nngroup.com/media/editor/2014/10/10/ux-landscape-questions.png)

#### The Context of Product Use

However there is a third dimension that has to do with direct and indirect use of the product of the service and the setting therein. In UXPin's [The Guide to Usability Testing](http://gibbon.co/c/1ada73ea-1f19-450d-bc35-64c6c436bcae/the-guide-to-usability-testing-free-ebook-by-ux) they have summarized Rohrer's note as—

```
1. Scripted use of the product — These tests focus on specific usage aspects.
The degree of scripting varies, with more scripting generating more controlled data.

2. Decontextualized use the product — Tests that don’t use the product
— at least in the actual testing phase — are designed for broader topics like UX or generating ideas.

3. Natural (and near-natural) use of the product — 
These tests seek to analyze common usage behaviors and trends with the product, 
doing well with data authenticity at the cost of control.

4. Hybrid — Hybrid tests are creative and non-traditional tests. 
Geared towards understanding the users’ mentality, these tests vary in what they can accomplish.


The Guide to Usability Testing © 2010 - 2017 UXPin Sp. z o.o 

```

## Choosing the right tasks

## Other Considerations

In addition to the dimensions described by Rohrer, your test methodology also depends on-

- functionality afforded by the prototype
- access to testing tools and equipment


## Putting a stake in the ground

WIP

— so many decisions can seem overwhelming

— but in reality goals and constraints help determine direction

— we are testing for diagnostic reasons not scientific so it is okay to use hybrid methods without too much rigidity

- Our aims are not purely scientific and still need to be adjusted to meet stakeholder needs. 

— we are testing overall UX not a very specific part, so it is okay to have broad open ended taks

— sample size is limited


### Prototype fidelity
While some believe in testing early with rough prototypes and others advocate testing higher fidelity prototypes, we believe the best approach is to test at every fidelity possible — and as often as possible. Chris Farnum, the Senior Information Architect at Enlighten, explains the pros and cons of each type. As we’ll describe below, lower fidelity tests are better for testing concepts while higher fidelity tests are more suitable for testing advanced interactions.
the best approach is to test at every fidelity possible
Low fidelity: lo-fi prototype usability tests, including paper prototypes, can work at the early stages of development, but become impractical later on. Lo-fi prototypes also encourage more honest criticism, since it’s immediately clear that it’s just a work in progress.
However, at the later stages, when usability tests check advanced functionalities, lo-fi prototypes stop becoming helpful since you’ve hit the fidelity limit. This is especially true for paper prototypes, since you need a “human computer” to manipulate all the parts, and that can become extremely difficult as you add menus, interactions, pages, and elements.
High fidelity: hi-fi prototype testing gives the user a near-realistic experience of what the final product will be like. Hi-fi prototypes are ideal for testing complex interactions and your solutions for usability issues discovered in earlier rounds of testing. However, unlike lo-fi prototypes, these are costlier to make.
Medium fidelity: can’t decide between high or low fidelity? Mid-fi prototypes work best when you need a balance between fidelity and cost. If you’re only going to run one round of usability tests, go medium fidelity.


### Moderated or Unmoderated?
One of the first questions usability testers ask is whether or not it should be moderated. While there are a lot of good reasons for unmoderated tests, for prototype tests we recommend moderation. Given the “incomplete” nature of prototypes, chances are that users will have questions about the UI that a moderator will have to answer.

Another common mistake in testing is to stop or alter the test if the user experiences difficulty. Since the goal of usability testing is to find and solve difficulties, this situation could actually make the test a success. If, for example, the user strays off onto paths that haven’t been developed yet in the prototype, you could ask them why they went there and what they would have liked to accomplish. A few follow-up questions about the obstacles may yield more valuable feedback than a user with a “perfect run”.
