# investigating a drop
 
**The Problem.**

&quot;How did our weekly engagement drop 21% in a month?!&quot;

**Job:**

to identify the cause of this sudden drop in engagement and suggest possible next steps and solutions.

**Procedure;**

brainstorming and trying to understand the possible causes of that drop.

Then, I will look at the data and use SQL to check my assumptions. After I have learned of which potential cause is more probable, I will draw up suggestions of solutions and next steps.

**Factors/Possible Causes:**

**Time** : Time is a good factor to consider since irregular trends are easier to spot when graphed. Here are the most common time-related data questions to ask yourself:

**Is it a one time occurrence or a recurring issue?** ⟶ a one time occurrence is likely due to a technical issue or marketing campaign while recurring issues could be due to behavioural changes.

_ **Do we see specific times during the day or specific days of the week where the drop is more pronounced?** _ ⟶ Drops localized to a specific time or day would likely indicate a technical issue — such as failed data refreshes that generally occur over the weekend

**Region** : Regional engagement levels are important to consider since companies may roll out features with specific regions when testing new products or regional internet censorship/ laws that can limit usage. Some questions to ask are:

_ **Do we see the drop in engagement tied to a particular region or is it globally distributed?** _

**Other Features / Products** : keeping general tabs on other products/features within the same space is useful for identifying potential changes at a company level. Some questions to ask are:

_ **Are other features or products also experiencing similar drops in engagement?** _ ⟶ if the drop is prevalent across other products and features, then the issue would be a larger problem that requires involvement from multiple teams to investigate

Are other similar features or products within the ecosystem experiencing a proportional increase in engagement?

**Platform** :

Do we see the decline in occurring across specific platforms (ie. mobile, desktop, tablet) or across all platforms?

**Outreach** : Yammer uses email communication to stay in touch with their users. Every week, two types of emails are sent: the weekly digest and the reengagement email. Yammer were able to track whether users opened the emails and whether they interacted with the content by clicking on the embedded links. **We can test to see if emails are the cause of the issue by looking at how users interact with their emails in August.**

**Database problem:** There is an error in the database pipeline and it is not recording user activities or it is recording it but sending information to the wrong place. To test this, we can check all the database and links and formula in it.
