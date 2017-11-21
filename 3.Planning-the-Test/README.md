## The Complexity in our Stars or Why Data Viz is inherently hard to test
*WIP needs attribution and citations*

### Faster is not necessarily better

Visualization is outcome driven. Very rarely are our users making  visceral decisions based on a vis, and while we care about the affective value of a vis, we don’t want them making emotional decisions (as we would on an ecommerce site). We don’t want to penalize a vis because it makes a user think. Similarly, no. of errors is not a good measure either.

### Too many moving parts
While for some usability studies, there may be an obvious and limited set of interface elements that should be tested. In many cases, however, the system is complex, new to the researcher, or the list of candidate features for testing is long. The following image demonstrates how quickly typographic elements can scale up in a dashboard, moving well beyond the typical h1, h2, h3, and so on,  elements used in websites.
![](../Assets/images/Chart-UI-components.png)

This section explores the wide array of research methods availale to research methods and then makes some decisions about which methods are recommended in

### Deciding Test Methodology


**Attitudnal vs. Behavioral**
> This distinction can be summed up by contrasting "what people say" versus "what people do" (very often the two are quite different). The purpose of attitudinal research is usually to understand or measure people's stated beliefs, which is why attitudinal research is used heavily in marketing departments.



**Quantitative vs. Qualitative Dimension**
Both quantitative and qualitative methods are valid for evaluating visualizations. You can choose to just go with one method or use a combination of both depending what you are trying to measure. Quantitative methods usually include close ended questions where something is measured on a scale. Qualitative methods include more open ended questions to get descriptive and free form feedback. Using the quantitative method, you can create a survey that measures how useful users found a visualization on a scale of 1 to 5. You can then use the qualitative method to ask users who entered a low rating a follow up question on why they did not find application useful. Quantitative methods will identify the strengths and weakness of your data visualization. Qualitative methods will uncover the "why" or the cause of those strengths/weaknesses.
https://www.nngroup.com/articles/quant-vs-qual/


This graphic from the NNGroup website succinctly sums up the landscape-
![User Research Methods Landscape](https://s3.amazonaws.com/media.nngroup.com/media/editor/2014/10/10/ux-landscape-questions.png)



## Planning your Test
https://projects.invisionapp.com/d/main#/projects/boards/4517347

A usability test is a technique to uncover UX design problems with actual users of the system.

### What do you need?

- A purpose- knowing why you are testing is very important; Use the [previous section](../2. Determining what to measure) to decide what you plan to test
- A prototype- you can use prototypes of varying fidelity ranging from a paper prototype to an interactive mockup.


- Users- The number of users you need to recruit for a test depends on your research methods. Generally, Quantitative studies require 


- Facilitator- Usually, a usability professional and whose role is to record the issues raised during the meeting.


- Human Computer(for paper prototypes)- This person (typically the lead developer or someone who knows how the system is supposed to work) manipulates the paper prototype so that it can provide the feedback based on the user’s interaction.
- Instruments/ Tools to capture test results eg. a questionnnaire, a time-recording software etc.

[Source](http://usabilitygeek.com/paper-prototyping-as-a-usability-testing-technique/)

A more comprehensive checklist : https://www.nngroup.com/articles/usability-test-checklist/




### Choosing the Right Test

In the free [Guide to Usability Testing](http://proxystudio.uxpin.com/ebooks/guide-to-usability-testing/), we divide the tests into four categories based on Christian Rohrer’s [fantastic article](http://www.nngroup.com/articles/which-ux-research-methods/):

- **Scripted** —These tests analyze the user’s interaction with the product based on set instructions, targeting more specific goals and individual elements. (tree testing, hallway usability tests, benchmark testing)


- **Decontextualized** — Ideal for preliminary user testing and persona research, these tests don’t necessarily involve the product, but analyze more generalized and theoretical topics, targeting idea generation and broad opinions. (user interviews, surveys, card sorting)


- **Natural (or near-natural)** — By analyzing the user in their own environment, these tests examine how users behave and pinpoint their feelings with accuracy, at the cost of control. (field and diary studies, A/B testing, first click testing, beta testing)


- **Hybrid** — These experimental tests forego traditional methods to take an unparalleled look at the user’s mentality. (participatory design, quick exposure memory testing, adjective cards)

  [Source](https://www.uxpin.com/studio/blog/how-to-run-an-insightful-usability-test/)




*Brain dump Examples of what all can be tested-
Tradeoffs involved
… Hence, one has to be intentional about what to test.
- Open ended tests reveal all sorts of feedback, with a UI as complex as a dashboard this can pose a serious challenge as there are so many rabbit holes you could fall under*
- ​



References:
https://www.nngroup.com/articles/ux-research-goals-to-scenarios/
