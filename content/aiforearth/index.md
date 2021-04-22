---
title: "Estimate cropping cycles using remote sensing & AI"  # Add a page title.
summary: "aiforearth"  # Add a page description.
date: "2020-11-23T16:30:00Z"  # Add today's date.
# type: "widget_page"  # Page type is a Widget Page

reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/media/` folder).
header:
  caption: "Photo by Scott Goodwill on Unsplash"
  image: "harvest_scott-goodwill-unsplash.jpg"
---

Despite the ambitious goal of achieving hunger and poverty eradication by the United Nations, producing sufficient food to feed the ever-growing human population is facing unprecedented challenges across the globe. Agricultural production needs to double its current size within the next three decades to catch up with the increasing demands. 

As research and technology proceed, a substantial increase in crop outputs is made possible through agricultural intensification, and increasing annual cropping cycles is among the promising means for sustainable intensification with less impact on the environment. The United States (US) has long been a superpower of food producer and exporter in the world. Agriculture, along with its related industries, contributes over $1 trillion to the US’s gross domestic product and supports 22 million of the country’s total employment. 

Exports of maize from the US, for example, reached as high as 2.4 billion bushels in 2017, supporting many countries including Mexico and Japan. Among all the food types, crop undergirds the agriculture sector and maintains food security in the US, which pertains to other countries under the accelerated process of globalization. This is the impetus for reliable monitoring of cropland dynamics in the US. 

Relying on rich open-accessed satellite imagery data, we have generated classified maps of cropping cycles in 2018 using fused Landsat, Sentinel-2 and MODIS data. The overall accuracy is above 90%. The research project is on-going and will lead to global mapping of cropping cycles covering the conterminous US. 

{{< figure src="Croppheno.jpg" title="Crop phenological information revealed by remote sensing data and proved by ground images captured by cameras" >}}

We integrate AI and remote sensing to automatically estimate annual cropping cycles at a fine spatial resolution (30m) in the conterminous US during 2013-2020. The estimation is made specifically by first optimizing the selection of temporally and spatially stable pixels as training samples and then classifying cropland pixels with information of annual cropping cycle(s) through integrating machine learning algorithms. 

{{< figure src="procedure.jpg" title="Flowchart of estimating pixel-based crop harvesting information" >}}

We will use advanced machine learning modules to analyze the “surface” of histograms of NDVI difference to select training sample, and then to automatically classify pixels about the information of cropping cycles. 

{{< figure src="fig1_US.png" title="Figure 1. Study Area: the contiguous United States with four selected regions" >}}

{{< figure src="fig2_thresholds.png" title="Illustration of stable pixle labeling with tuning parameters" >}}


 <br>
 
_Qi Zhang_
_April 21, 2021_
 
 <br>

*Related Links:* <br>
[News in Pardee Center](https://www.bu.edu/pardee/2020/05/27/postdoc-qi-zhang-awarded-microsoft-ai-for-earth-grant/) <br>
[Open source data - global cropping cycles](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/86M4PO) <br>
[Publication - a new framework to map global cropping cycles](https://www.sciencedirect.com/science/article/abs/pii/S0034425720304685) <br>
[Labeled pixels: Region 1](https://drive.google.com/file/d/1iXzZc92ncc7Nd3b0y2glM3F_5f7magZs/view?usp=sharing) <br>
[Labeled pixels: Region 2](https://drive.google.com/file/d/13XbnfwPe73aCO-8uxGLX3cWT7oqWwvcS/view?usp=sharing) <br>
[Labeled pixels: Region 3](https://drive.google.com/file/d/1vvKCmwZrydTEyijUgNBtkn4GVr89Y7Dm/view?usp=sharing) <br>
[Labeled pixels: Region 4](https://drive.google.com/file/d/19rTXU52M4VMmJ807S-ZEcZLko_sG71LL/view?usp=sharing) <br>
 <br>
