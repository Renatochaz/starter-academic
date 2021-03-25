---
title: Visualizing salary and investment data
summary: Dashboard made with Tableau for salary data from US foreign employees and investment data from Brazilian Bovespa firms
tags:
- Visualization
- Tableau
- Investment
- US salary
date: "2021-03-25T01:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
- icon: ""
  icon_pack: ""
  name: ""
  url: ""
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Building some dashboards to visualize different types of data. 

Here we will visualize two datasets: The first is from US salary for foreigners, and the second is about investment from Brazilian Bovespa firms and its relationship with political uncertainty.



# US salary for foreigners

Have you ever thought about working in the US? If you had, one important question you should address is how much will you make over there. 

Some questions you might want to answer would be:

- Is the salary higher than in my country? 
- Do different states pay different wages?
- Which companies have better wages?
- Is my profession growing or declining in salaries over the years?

To answer this questions, i collected performance data from the [US Labor Department](https://www.dol.gov/agencies/eta/foreign-labor/performance) from 2008 to 2015 and adjusted to some professions you might work. I'm particularly interested in data related jobs, so those are the focus of the analysis.



To access the dashboard and adjust to your own accord, please go to [Dashboard US Salaries](https://public.tableau.com/profile/renato.chavez#!/vizhome/Modified_us_salary4/Dashboard2).



In the overview image below we already see some interesting information. 

We can see that data scientists and software engineers gain on average much more than data and bi analysts. 

Washington, California and Massachusetts are the  top wage states for data scientists and software engineers, but not for data and bi analysts.

It seems that foreign workers gain a little more than the prevailing wage, which kind makes sense, if you go to the trouble of hiring someone overseas you might want to attract then with a good wage.

{{< figure src="featured.jpg" title="Overview US salaries" numbered="true" >}}



Now let us take a quick look in how can we answer some specific answer: If we want to work as a data analyst, what information can we take from here?

Looking at the image below we see that although Alabama is the top paying state, there doesn't seen to be a huge difference between wage in different states. We can expect to make about $70.000 annually, and the trend line indicates that the median wage is growing over the years, yay! Additionally, it seems that the company INTUIT in California is paying some really high wages, so you might want to try a position there to consider going to the US? 


Feel free to explore the dashboard and look at different jobs! 

{{< figure src="salary1.jpg" title="Data Analyst data" numbered="true" >}}



# Brazilian firms investment data and political uncertainty

The dataset used in this dashboard comes from my research of investment and political uncertainty. Because the objective of the research is do a inference of uncertainty on investment, the data was adjusted to minimize possible bias. 

Although the data can still be used to understand the private scenario of investment, you should note that:

The observations are at firm-level and quarterly financial statements, ranging from the third quarter of 2005 to the last quarter of 2019;

All relevant accounting information must be available for a given firm for at least 8 consecutive quarters to be included in the research;

Financial and investment fund sectors are not included in the sample;

To download and interact with the dashboard, please go to [Dashboard Link](https://public.tableau.com/profile/renato.chavez#!/vizhome/Investimentoeincertezapoltica/Dashboard1).

Now, looking at the image below we can understand the big picture. It is clear that the investment dropped in 2009, had a quick recovery in 2010 but started to decline until 2016, when it started to recover. This is what you would expect, since the financial crises of 2008 setback and the start of a recession in the economy from 2011 onwards.

When looking at financial constraints, although bot groups have declined the investment levels, note that financial constrained firms had some sharper depressions, which is also expected, because periods of crises usually rises credit costs, making financial constrained firms even more dependents on internal funds.

{{< figure src="inv1.jpg" title="Investment and Political Uncertainty" numbered="true" >}}

When we look at the contrast of political uncertainty x investment, it becomes clear that when investment falls, political uncertainty rises. There seems to be a significant negative effect of uncertainty on investment, but to actually measure this effects is a pretty hard econometric challenge. If you are interested, feel free to look at my research project page.



We can also look at specific economic sectors. When looking at the chemical sector,  we can see that it looks like it is almost unaffected by crises or uncertainty, although it had some falls, it remains less sensitive that the overall scenario.

{{< figure src="inv1.jpg" title="Chemical sector" numbered="true" >}}



For further inquiries about the specifics of the project contact me at: renato.ch@usp.br




