## The Complexity in our Stars or Why Data Vis is inherently hard to test

### Faster is not necessarily better

Visualization is outcome driven. Very rarely are our users making  visceral decisions based on a vis, and while we care about the affective value of a vis, we don’t want them making emotional decisions (as we would on an e-commerce site). We don’t want to penalize a vis because it makes a user think. Similarly, no. of errors is not a good measure either. 

### Too many moving parts
While for some usability studies, there may be an obvious and limited set of interface elements that should be tested. In many cases, however, the system is complex, new to the researcher, or the list of candidate features for testing is long. In many cases, visualizations are exploratory in nature. This would require a full functional application that the user can dynamically interact with. Creating a prototype that simulates a fully functional application is challenging. The following image demonstrates how quickly typographic elements can scale up in a dashboard, moving well beyond the typical h1, h2, h3, and so on,  elements used in websites.
![](../Assets/images/Chart-UI-components.png)

### Insights are hard to measure
The ability to draw insights is key for data visualizations. If you want to measure how many insights are derived using one visualization versus another, how do you define what constitutes an insight in the first place? Also, the definition of an insight can vary from user to user.

### Datum Ipsum

It is time-consuming to produce hi-fidelity [looks-like and works-like prototypes](https://dschool-old.stanford.edu/groups/k12/wiki/e7aa3/Looks_likeWorks_like.html) with real-data backing them. While we do attempt to use meaningful placeholder data,  static mockups can only show so much.

Tools- http://datumipsum.com/

