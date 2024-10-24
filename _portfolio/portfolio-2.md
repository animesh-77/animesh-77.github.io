---
title: "Geospatial Analyst Intern at Pixxel"
excerpt: "Monitoring crop phenology using satellite images and machine learning <br/><img src='/images/Pixxel.png' width='50%'>"
collection: portfolio
---

# Overview

Starting my career as a Geospatial Analyst Intern at [Pixxel](https://www.pixxel.space/about-us), India's leading space startup, was an incredible opportunity right after earning my degree in physics. It provided the perfect environment to apply my academic knowledge to real-world challenges and grow professionally.

My work focused on utilising multispectral satellite imagery to monitor crop phenology. In simpler terms, it aimed to track the growth cycles of crops at an individual farm level using only satellite images. *Why does it matter?* As it turns out, crop phenology is highly valuable as it enables the prediction of various metrics such as per hectare yield, water consumption, and facilitates improved agricultural management practices.

<figure>
  <img src="/images/crop_phenology.png" alt="Crop phenology through images" style="width:100%">
  <figcaption>Crop phenology. <em>Credits: Taylor, S.D.; Browning, D.M. Classification of Daily Crop Phenology in PhenoCams Using Deep Learning and Hidden Markov Models.  </em></figcaption>
</figure>

The challenge was to create a model that could work across different locations and crop types, while also being scalable to larger areas. However, the lack of available ground truth data posed a challenge, requiring me to generate a dataset for evaluating the performance of the model.

I developed a Python-based pipeline using GDAL , Rasterio (and PySTAC, Rioxarray and many others) libraries to process and analyze multispectral satellite images. The pipeline included tasks such as image preprocessing, feature extraction, and classification using machine learning algorithms.

Additionally, I created a web-based dashboard using Plotly/Dash to present the crop phenology data in an interactive and user-friendly way. This dashboard helped me get useful feedback from the team and management, which was crucial for improving the model in subsequent iterations.
The model was later deployed on Pixxel's platform, which offers a comprehensive solution for all geospatial requirements. The platform includes various machine learning and physics-based models that provide valuable insights into satellite imagery.
