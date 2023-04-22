---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Store Sales - Time Series Forecasting"
summary: 'In this project, we present machine learning techniques to predict store sales in the <a href="https://kaggle.com/competitions/store-sales-time-series-forecasting">Store Sales - Time Series Forecasting</a> competition on Kaggle. We were asked to forecast 15 days (2017-08-16 to 2017-08-31) of store sales for Corporación Favorita, a large Ecuadorian-based grocery retailer. The provided data consisted of the past sales for 33 families of items from 54 stores over the period of 2013-01-01 to 2017-08-15. Additionally, we were given information on past oil prices, holidays, and store locations to potentially aid our forecast. We began by determining a baseline score with a basic linear regression model. With this score in mind, we experimented with decision tree-based models. After unimpressive results , we further explored the provided datasets to identify potential trends, seasonal patterns, and features that were relevant to the forecast. Finally, we trained various models on our enriched feature set and settled on the one that gave us our best score: a version of an ExtraTreesRegressor.<br><br>
  This project was done towards coursework of CSCI 567: Machine Learning, Fall 2022, USC.'
authors:
  - admin
  - Prashanth Ravichandar
  - Gaurav Aidasani
  - Kyle Manke
tags: []
categories: []
date: 2022-12-14T23:56:51-08:00

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/ksanu1998/store_sales_forecasting"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  # caption: ""
  focal_point: "Top"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/ksanu1998/store_sales_forecasting"
url_pdf: "CSCI567_id1_Project_Report.pdf"
url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""
---
