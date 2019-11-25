---
layout: page
title: Optimizing CTR with Deep Learning
description: 2015-2017
img: /assets/img/projects/CTR/diagram.png
---

This is a project I started on sophomore year at Purdue through an NSF Research Experiences for Undergraduates grant 1246818. This would not been possible without the [Statistics Living Learning Community](http://llc.stat.purdue.edu) that I was part of that year, headed by Prof. Mark Daniel Ward.

The project I worked is based on the fact that a large part of electronic retail relies on understanding consumer product interests. This has led to the development of mathematical models in advertisement agencies to predict if the consumer they are targeting will click on their advertisement. Achieving the highest click prediction rate would mean that these agencies can pay to place their on line advertisements effectively to target people most interested in their product. Most of these predictions are based on regression models. Our goal was to utilize deep learning models to achieve better scores than the known regression models.

The data that we used was from the iPinYou competition, where competitors were tasked to build a model that would achieve a high click through rate (CTR). iPinYou provided advertisement data from 9 companies. For each instance in the data we were given various attributes of the person that the electronic advertisement was sent to as well as if the person clicked on the advertisement. The data was originally split into different seasons of the iPinYou competition so the data for each advertiser had to be aggregated. After that, some of the variables had to be removed, spliced, or one hot encoded. 

Once we had our data we tested our predictive power using a convolutional neural net and then a neural network model. Using our model configuration, we were not able to achieve higher predictive power than the regressions we compared it to, but the way we arranged our data made our models more interpretable to further analysis.

<figure>
    <img src="/assets/img/projects/CTR/diagram.png" style="width:700px;height:350px;">
    <figcaption>CNN model visualization</figcaption>
</figure>

I was advised by Dr. Xiao Wang and Dr. Quiang Liu at Purdue. The results are going to be published in [JPUR](http://docs.lib.purdue.edu/jpur/) 2017.