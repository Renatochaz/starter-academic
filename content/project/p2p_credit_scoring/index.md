---
title: P2P Credit scoring 
summary: Credit scoring research in P2P lending system using LendingClub data
tags:
- Credit scoring
- P2P
- Lending
- Logistic regression
date: "2021-01-14T01:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
- icon: file-pdf
  icon_pack: fas
  name: PDF
  url: media/Artigo_MQA_Renato_Chavez_final.pdf
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
My first applied project at the master's course in Econometrics was to do a credit scoring model using the Lending Club data. Lending Club is a massive peer-to-peer lending platform launched in 2011 with almost $100 billion in transactions as of January/2021.

 Using ~ 1 million observations from [Lending club open lending operations](https://www.lendingclub.com/info/statistics.action) between 2012~2018, this project aim was to research the literature of credit scoring to understand which personal data contains information about good and bad lenders. With a set of selected variables and running logistic regressions the best model got a 68% accuracy to distinguish bad lenders. 

All detailed information about the P2P operations, selected variables, data treatment, models and results are available at the {{% staticref "media/Artigo_MQA_Renato_Chavez_final.pdf" "newtab" %}}PDF link{{% /staticref %}} in this post.

Unfortunately the R project with the code isn't available, but all data can be downloaded for free in the Lending club page and the same regression described in the paper can be used.

For further inquiries about the specifics of the project contact me at: renato.ch@usp.br




