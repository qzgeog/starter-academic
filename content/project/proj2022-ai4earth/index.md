---

# Documentation: https://wowchemy.com/docs/managing-content/

title: "Cropland Dynamics and Remote Sensing"
summary: "Mapping continuous cropping cycles over large scales"
authors: [Qi Zhang, Shiqi Tao, Chong Liu]
tags: [AI for Earth, cropland dynamic, machine learning, remote sensing]
categories: [Earth Science]
date: 2021-05-15T12:00:09-05:00

reading_time: true  # Show estimated reading time?

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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

# Optional header image (relative to `static/media/` folder).
header:
  caption: "Photo by Scott Goodwill on Unsplash"
  image: "header1_harvest.jpg"

---

Despite the ambitious goal of achieving hunger and poverty eradication by the United Nations, producing sufficient food to feed the ever-growing human population is facing unprecedented challenges across the globe. Agricultural production needs to double its current size within the next three decades to catch up with the increasing demands. 

As research and technology proceed, a substantial increase in crop outputs is made possible through agricultural intensification, and increasing annual cropping cycles is among the promising means for sustainable intensification with less impact on the environment. The United States (U.S.) has long been a superpower of food producer and exporter in the world. Agriculture, along with its related industries, contributes over $1 trillion to the US’s gross domestic product and supports 22 million of the country’s total employment. 

Exports of maize from the U.S., for example, reached as high as 2.4 billion bushels in 2017, supporting many countries including Mexico and Japan. Among all the food types, crop undergirds the agriculture sector and maintains food security in the US, which pertains to other countries under the accelerated process of globalization. This is the impetus for reliable monitoring of cropland dynamics in the US. 

Relying on rich open-accessed satellite imagery data, we have generated classified maps of cropping cycles in 2018 using fused Landsat, Sentinel-2 and MODIS data. The overall accuracy is above 90%. The research project is on-going and will lead to global mapping of cropping cycles covering the conterminous US. 

{{< figure src="phenophase.jpg" title="Crop phenological information revealed by remote sensing data and proved by ground images captured by cameras ([Liu et al. 2020](https://www.qzgeog.com/publication/p2020-liu-crop/))" >}}

We integrate artificial intelligence and remote sensing to automatically estimate annual cropping cycles at a fine spatial resolution (30m) in the conterminous US during 2013-2020. The estimation is made specifically by first optimizing the selection of temporally and spatially stable pixels as training samples and then classifying cropland pixels with information of annual cropping cycle(s) through integrating machine learning algorithms. 

{{< figure src="workflow.jpg" title="Flowchart of estimating pixel-based crop harvesting information (by Shiqi Tao)" >}}

We will use advanced machine learning modules to analyze the “surface” of histograms of NDVI difference to select training sample, and then to automatically classify pixels about the information of cropping cycles. 

{{< figure src="fig1_US.png" title="Figure 1. Study Area: the contiguous United States with four selected regions" >}}

{{< figure src="fig2_alpha.png" title="Figure 2. Illustration of stable pixle labeling with tuning parameters" >}}

{{< figure src="fig3_estimates.png" title="Figure 3. Maps of stable pixels and classified cropping cycles" >}}
<br>

Funding
- [Microsoft AI for Earth](https://www.microsoft.com/en-us/ai/ai-for-earth) Azure Computing Grant, PI: [Qi Zhang](https://www.qzgeog.com/)
- [American Association of Geographers (AAG)](http://www.aag.org/) Research Grant, PI: [Qi Zhang](https://www.qzgeog.com/)
<br>

Publications
- [Mapping global cropping intensity](https://www.sciencedirect.com/science/article/abs/pii/S0034425720304685)
  ([Liu et al. 2020](https://www.qzgeog.com/publication/p2020-liu-crop/))
<br>

<br>

Related Links
- [News in Frederick S. Pardee Center at Boston University](https://www.bu.edu/pardee/2020/05/27/postdoc-qi-zhang-awarded-microsoft-ai-for-earth-grant/) <br>
- [Twitter](https://twitter.com/theAAG/status/1367150369021779974) by American Association of Geographers <br>
<br>

<br>
<br>
<br>

_Authors: Shiqi Tao, Qi Zhang_
<br>
_Updated: April 21, 2021_


