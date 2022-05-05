---
layout: single
title: "Portfolio"
permalink: /portfolio/
header:
    overlay_image: /assets/images/sky-line1.jpg
author_profile: true
classes: wide
date: May 4, 2022

feature_row1:
  - image_path: /assets/images/wnba.gif
    alt: "WNBA app"
    title: "WNBA Player Analysis App"
    text: "Streamlit app that leverages the results of my WNBA shot probability model and turns it into an interactive UI."
    url: "https://share.streamlit.io/maxbolger/wnba-player-analysis-app/main"
    btn_label: "Streamlit App"
    btn_class: "btn--primary"
    url2: "https://github.com/maxbolger/wnba-player-analysis-app"
    btn_label2: "App Code"
    btn_class: "btn--primary"
    url3: "https://github.com/maxbolger/CDS-5950-Capstone"
    btn_label3: "ML/Web Scraping Code"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/clf.png
    alt: "Voting classifiers"
    title: "Voting Classifier App"
    text: "Streamlit app that allows users to experiment with voting classifiers by using the Palmer Penguins data."
    url: "https://share.streamlit.io/maxbolger/voting-classifier-app/main"
    btn_label: "Streamlit App"
    btn_class: "btn--primary"
    url2: "https://github.com/maxbolger/voting-classifier-app"
    btn_label2: "App Code"
    btn_class: "btn--primary"
    
feature_row3:
  - image_path: /assets/images/viz.gif
    alt: "Data Viz"
    title: "Advanced Data Visualizations"
    text: "Advanced data visualizations created with matplotlib and seaborn using #TidyTuesday data"
    url: "https://github.com/maxbolger/CDS-5950-Data-Viz-Challenges"
    btn_label: "Data Viz Repo"
    btn_class: "btn--primary"
    
feature_row4:
  - image_path: /assets/images/nflfastr.png
    alt: "nflfastR"
    title: "nflfastR Python Tutorial"
    text: "Tutorial on how to analyze NFL play-by-play data (courtesy of [nflfastR](https://www.nflfastr.com/)) using python and its data science resources. Covers basic python syntax, exploratory data analysis (EDA), one-hot encoding, data visualization, creating a function, and more!"
    url: "https://github.com/maxbolger/nflfastR-Python-Tutorial"
    btn_label: "Tutorial Repo"
    btn_class: "btn--primary"
    
feature_row5:
  - image_path: /assets/images/sleeper.png
    alt: "Sleeper"
    title: "Sleeper API Python Tutorial"
    text: "Tutorial on how to utilize the [Sleeper](https://sleeper.app) API to obtain data and run analyses on fantasy football leagues. Covers basic python syntax and utilizes multiple packages."
    url: "https://github.com/maxbolger/Sleeper-API-Tutorial"
    btn_label: "Tutorial Repo"
    btn_class: "btn--primary"
    
    
---

{% include feature_row id="feature_row1" type="left" %}
<a name="WNBA Project"></a>
{% include feature_row id="feature_row2" type="left" %}
<a name="Voting Classifier"></a>
{% include feature_row id="feature_row3" type="left" %}
<a name="Data Viz"></a>
{% include feature_row id="feature_row4" type="left" %}
<a name="nflfastr tutorial"></a>
{% include feature_row id="feature_row5" type="left" %}
<a name="Sleeper tutorial"></a>
