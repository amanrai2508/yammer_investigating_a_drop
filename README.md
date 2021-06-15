# Investigating a drop in user Engagement
 
# The Problem

# **Job:**

to identify the cause of this sudden drop in engagement and suggest possible next steps and solutions.
<div class='tableauPlaceholder' id='viz1623776556559' style='position: relative'><noscript><a href='#'><img alt='Investigating a drop ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;JM&#47;JMQ3RNQ97&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;JMQ3RNQ97' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;JM&#47;JMQ3RNQ97&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>      


# **List of Tables**

![image](https://user-images.githubusercontent.com/37997480/122095545-271c1700-ce2b-11eb-8983-49cd90ea7301.png)


![image](https://user-images.githubusercontent.com/37997480/122095186-abba6580-ce2a-11eb-9e09-4efbc589da4d.png)

![image](https://user-images.githubusercontent.com/37997480/122095809-76fade00-ce2b-11eb-802a-4fb5ea1cb455.png)

![image](https://user-images.githubusercontent.com/37997480/122095715-59c60f80-ce2b-11eb-9e57-a10550af2913.png)

# **SQL(Functions Used)**
Basic SQL syntax

SQL aggregate functions

Joining tables

Writing subqueries

Pivoting data in SQL

# **Procedure**

brainstorming and trying to understand the possible causes of that drop.

Then, I will look at the data and use SQL to check my assumptions. After I have learned of which potential cause is more probable, I will draw up suggestions of solutions and next steps.

# **Factors/Possible Causes:**

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

# **Story and Visualizations**
<div class='tableauPlaceholder' id='viz1623777728174' style='position: relative'><noscript><a href='#'><img alt='Investigating a drop ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;InvestigatingADrop&#47;Investigatingadrop&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='InvestigatingADrop&#47;Investigatingadrop' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;In&#47;InvestigatingADrop&#47;Investigatingadrop&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>               

# **Link**
https://public.tableau.com/views/InvestigatingADrop/Investigatingadrop?:language=en-US&:display_count=n&:origin=viz_share_link
