---
title: Demand forecast in R
summary: Demand forecast for a private supermarket chain in São Carlos.
tags: 
- Demand forecast
- R
- Data science
date: "2021-01-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/Renatochaz/L1---Demand-Forecasting
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

*** This is a private work, data isn't avaliable and identification of the client is omitted ***

A local supermarket chain was interested in forecasting their produce section, they manually estimated when to buy and had a huge waste of food going bad before selling.

Their database had over 20 years of information from all stores, the data was unustructured when minned. We made a functional code to structure the data and propposed a SARIMA model with paramater variation for every item in the produce section.

The model worked out in mixed ways for the items, some were analyzed to be totally random and the model coudn't predict accuratelly, while some had a accuracy of over 95%.

Full disclosure of the project details isn't possible due to the private nature of the work, for further inquiries about the specifics of the project contact me at: renato.ch@usp.br

Below are some images of the work

{{< figure src="raw_data.jpg" title="Unustructured data minned from database" numbered="true" >}}

{{< figure src="clean_data.jpg" title="Data after processing in R" numbered="true" >}}

{{< figure src="plot_time_data.jpg" title="Time series plot for analysis" numbered="true" >}}

{{< figure src="decomposition.jpg" title="Plots of autocorrelation in the SARIMA model" numbered="true" >}}

{{< figure src="featured.jpeg" title="Unique item weekly forecast with 80% accuracy" numbered="true" >}}


