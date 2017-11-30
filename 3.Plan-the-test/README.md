# Table of Contents
 
  * [Planning your Test](#planning-your-test)
    * [Recruiting users/evaluators for your test](#recruiting-users-or-evaluators-for-your-test)
    * [Choosing the right test](#choosing-the-right-test)
    * [Choosing the right tasks](#choosing-the-right-tasks)
    * [Preparing your prototype](#preparing-your-prototype)
  * [Putting a stake in the ground](#putting-a-stake-in-the-ground)
  * [References](#references)


# Planning your test

Usability testing can uncover *all kinds* of feedback. As such, the foremost step in planning our test is picking a direction for the test. The previous sections help us frame questions about what we want to get out of the test but there is still the lingering question—how do you actually execute the test?

A quick search on Usability.gov reveals more than just a few methods to garner feedback from users from—baseline [usability testing](https://www.usability.gov/how-to-and-tools/methods/usability-testing.html) on an existing product/service to [first click testing](https://www.usability.gov/how-to-and-tools/methods/first-click-testing.html) to make sure our users go down the right path to satisfaction [surveys](https://www.usability.gov/how-to-and-tools/methods/online-surveys.html) to see how our product/service  fares in the real world.

And while at first this choice can seem overwhelming, it is important to realize that real-life constraints such as our research questions or our users' availability can help us narrow down the choices. In the next section we will attempt to break down the various steps involved when planning a usability test and provide some guidelines for each.

## Recruiting users or evaluators for your test

> After all the work with personas, by now you should have a clear idea of your target users. It also helps to segment your users based on behavior. In fact, you shouldn’t obsess over demographics. The biggest differentiator will likely be whether users have prior experience or are knowledgeable about their domain or industry — not gender, age, or geography.
> Knowing who to recruit is just the first step. The more involved part is finding and recruiting them. Jeff Sauro outlines the 7 best ways to [locate the ideal users](https://measuringu.com/finding-users/) for your testing.

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

#### Other Considerations

In addition to the dimensions described by Rohrer, your test methodology also depends on-

- **Fidelity of your prototype/functionality afforded by the prototype** 
Based on how sophisticated your prototype is, there may or may not be a need for human intervention during the test in order to ensure a smooth sailing experience. Chris Farnum, Senior Information Architect at Enlighten, has written a detailed article about using [prototypes for user testing](http://boxesandarrows.com/what-you-should-know-about-prototypes-for-user-testing/).

- **Access to testing tools and equipment**


## Choosing the right tasks

### Choose purposeful tasks
Usability Tests should be purposeful so as to not generate all kinds of feedback. Therefore, it is good to have specific tasks in mind when planning a Usability Test. Designing tasks should be a careful and thoughtful activity that [turns user goals into task scenarios](https://www.nngroup.com/articles/task-scenarios-usability-testing/). The example below descibes when Jared Spool was conducting a Usability test for IKEA with his team. 


> **The Task:** “Find a bookcase.”  
> **The Result:** All participants searched for 'bookcase' in the search box.  
> **The Spin:** Jared and his team decided to change this prompt to “You have 200+ books in your fiction collection, currently in boxes strewn around your living room. Find a way to organize them.”  
> **The Result:** User behavior changed. Most clicked through the various categories, looking for some sort of storage solution. Few used Search, typing in phrases like “Shelves” and “Storage Systems”. And, nobody searched on “bookcase”.  
>
> **Takeaway:** Tasks may direct users path in a way that is different from their context of use.You can get around this mistake by constantly exploring the “context of use.” When designing tasks, ask yourself, “What events or conditions in the world would motivate someone to use this design?” Use the answers as the primary formation of the tasks you create. 

Make the task actionable and realistic enough so that you as the moderator will need to provide as little guidance as possible. Avoid leading questions, giving hints, or describing step-by-step instructions, as this will skew the test toward your own bias.

### Choose the right format

Ubuntu has a great [blog post](https://design.canonical.com/2013/08/usability-testing-how-do-we-design-effective-tasks/) on choosing the right test that has been quoted below:

> The tasks could be categorised into two main formats:
>
> * Direct tasks or Scenario tasks
> * Open-ended or Closed task
>
> **Scenario task or Direct task**  
> A scenario task is presented as a mini user story: often it has the character, the context and the necessary details for achieving the goal.
>
> A direct task is purely instructional. 
>
> Among these two types, we often use the scenario tasks in the testing. This is because it emulates real-world context that participants can easily relate to, and consequently they are more likely to behave in a natural way. 
>
> **Closed task or Open-ended task**  
> A closed task is specific to what the participants need to do. This type of task has one correct answer, and therefore allows us to measure if participants solved or failed a task.
>
> An open-ended task contains minimum information and less specific direction as to what you want a participant to do. It gives users more freedom to explore the system.

![](/Assets/images/task-types.png)
### Pick the right order
It might make sense to place simpler tasks before more complex ones so users can familiarize themselves with the prototype at the beginning of the test. In some cases tasks are dependent on each other. For example, navigating to a home page could be the first task and reporting an issue on the home page could be the last task. Reversing the order would not make sense in this case. This is not always true though. Some tasks do not depend on each other and the order does not matter.


### Plan a test run
Always plan a test run before conducting the actual test. This will ensure that the prototype is working and all the tasks make sense. Put yourself in the users shoes during the test run and think about potential challenges that they might face. Think about how the user would interpret and go about tasks.

## Preparing your prototype
Jerry Cao, content strategist at UXPin, recommends the [following four content guidelines](https://www.webdesignerdepot.com/2015/02/how-to-test-the-usability-of-prototypes-like-a-pro/) for testing prototypes-
1. **Avoid lorem ipsum**: distracting, confusing, and lacking meaning, lorem ipsum text does not fully capture your product’s message.
2. **Use generic names**: tests may be more fun with silly or celebrity names, but fun isn’t the point. Any distractions will bias the results, so keep names generic and realistic.

3. **No placeholder images or icons**: boxes with Xs may work during wireframing, but not in testing. Images and icons play a large role in UX, so these should be implemented by testing time, even if only with temporary sketches. The exception is if these images are purely decorative and don’t help to understand the UI.

4. **Use realistic data** — Don’t fill data like phone numbers or addresses with Xs or jokes — these are distracting. Realistic and believable data here will give your user test the most accurate results.

# Putting a stake in the ground

WIP

— so many decisions can seem overwhelming

— but in reality goals and constraints help determine direction

— we are testing for diagnostic reasons not scientific so it is okay to use hybrid methods without too much rigidity

- Our aims are not purely scientific and still need to be adjusted to meet stakeholder needs. 

— we are testing overall UX not a very specific part, so it is okay to have broad open ended taks

— sample size is limited


### Moderated or Unmoderated?
> One of the first questions usability testers ask is whether or not it should be moderated. While there are a lot of good reasons for unmoderated tests, for prototype tests we recommend moderation. Given the “incomplete” nature of prototypes, chances are that users will have questions about the UI that a moderator will have to answer.
>
> Another common mistake in testing is to stop or alter the test if the user experiences difficulty. Since the goal of usability testing is to find and solve difficulties, this situation could actually make the test a success. If, for example, the user strays off onto paths that haven’t been developed yet in the prototype, you could ask them why they went there and what they would have liked to accomplish. A few follow-up questions about the obstacles may yield more valuable feedback than a user with a “perfect run”.

#References  
- https://articles.uie.comusability_testing_mistakes/ 
- https://design.canonical.com/2013/08/usability-testing-how-do-we-design-effective-tasks/
