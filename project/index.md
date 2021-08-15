---
date: 2021-06-16
title: "Project: Aquatic Animals Classification Using AI"
linkTitle: "fish classification"
tags: ["project", "reu", "ai", "biology, "detection"]
description: "Here comes the abstract"
author: Timia Williams
github_url: https://github.com/cybertraining-dsc/su21-reu-370/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-370/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-370/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-370/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-370/actions)
Status: draft, Type: Project


Timia Williams, [su21-reu-370](https://github.com/cybertraining-dsc/su21-reu-370), [Edit](https://github.com/cybertraining-dsc/su21-reu-370/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Marine animals play an important role in the ecosystem.  "Aquatic animals play an important role in nutrient cycles because they store a large proportion of ecosystem nutrients in their tissues, transport nutrients farther than other aquatic animals and excrete nutrients in dissolved forms that are readily available to primary producers" (Vanni MJ 1) Fish images are captured by scuba divers, tourist, or underwater submarines. different angles of fishes image can be very difficult to get because of the constant movement of the fish. In addition to getting the right angles, the images of marine animals are usually low-quality because of the water. Underwater cameras that is required for a good quality image can be expensive. Using AI could potentially increase the marine population by the help of classification by testing the usage of machine learning using the images obtained from the aquarium combined with advanced technology. We collect 164 fish images data from Georgia acquarium to look at the different movements. 

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** tensorflow, example. 

## 1. Introduction

It can be challenging to obtain a large number of different complex species in a single aquatic environment. Traditionally, it would take marine biologists years to collect the data and successfully classify the type of species obtained [1]. Scientist says that more than 90 percent of the ocean's species are still undiscovered, with some estimating that there are anywhere between a few hundred thousand and a few million more to be discovered" (National Geographic Society). Currently, scientists know of around 226,000 ocean species. Now and days, Artificial intelligence and machine learning has been used for detection and classification in images. In this project, We will propose to use machine learning techniques to analyze the images obtained from the Georgia Aquarium to identify legal and illegal fishing. 


## 2. Machine learning in fish species.

Aquatic ecologists often count animals to keep up the population count of providing critical conservation and management. Since the creation of underwater cameras and other recording equipment, underwater devices have allowed scientists to safely and efficiently classify fishes images without the disadvantages of manually entering data, ultimately saving lots of time, labor, and money. The use of machine learning to automate image processing has its benefits but has rarely been adopted in aquatic studies. With using efforts to use deep learning methods, the classification of specific species could potentially increase. In fact, there is a study done in Australia's ocean waters that classification of fish through deep learning was more efficient that manual human classification. In the study to test the abundance of different species, "The computer’s performance in determining abundance was 7.1% better than human marine experts and 13.4% better than citizen scientists in single image test datasets, and 1.5 and 7.8% higher in video datasets, respectively" (Campbell, M. D.). This remarkably explain that using machiene learning in marine animals is a better method than a manually classifying Aquatic animals Not only is it good for classification, it will be used to answer broader questions such as population count, the location of species, its abundance, and how it appears to be thriving. Since Machine learning and deep learning are often defined as one, both learning methods will be used to analyze the images and find patterns on my data.
 
## 3. Datasets

We used two datasets in my project. The first dataset includes the pictures that I took at the Georgia Acquarium. That dataset was used for testing. The second dataset used was a fish dataset from kaggle which contains 9 different seafood types (Black Sea Sprat, Gilt-Head Bream, Hourse Mackerel, Red Mullet, Red Sea Bream, Sea Bass, Shrimp, Striped Red Mullet, Trout). For each type, there are 1000 augmented images and their pair-wise augmented ground truths.

The link to access the dataset I used from kaggle is <https://www.kaggle.com/crowww/a-large-scale-fish-dataset>


## 3.1. Sample of Images of Personal Dataset

<img src="https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-370/main/project/images/IMG_1566.jpg" width="30%"> <img src="https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-370/main/project/images/IMG_1583.jpg" width="30%"> <img src="https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-370/main/project/images/IMG_1574.jpg" width="30%">

Left to right: Banded Archerfish, Lionfish, and Red Piranha 

**Figure 1:** These images are samples of my personal data which is made up of images of fishes taken at the Georgia Acquarium.

## 3.2. Sample of Images from Large Scale Fish Dataset

![Figure 1](https://raw.githubusercontent.com/cybertraining-dsc/su21-reu-370/main/project/images/IMG_1565.jpg)



## 4. Conclusion

Deep learning methods provide a faster, cheaper, and more accurate alternative to manual data analysis methods currently used to monitor and assess animal abundance and have much to offer the field of aquatic ecology. We was able to create a model to prove that we can use AI to efficiently detect and classify marine animals. 


## 5. Acknowledgments

Special thanks to these people that helped me with this paper:
Gregor von Laszewski 
Yohn Jairo 
Carlos Theran
Jacques Fleischer 
Victor Adankai

## 6. References

[^1]:  McIntyre P.B., Jones L.E., Flecker S.A., Vanni M.J. (2007) "Fish extinction alter nutrient recycling in tropical freshwaters", [Online resource]
       <https://www.pnas.org/content/104/11/4461>

[^2]:  National Geographic Society (2021) "Ocean", [Online resource]
       <https://www.nationalgeographic.org/encyclopedia/ocean/>

[^3]: Gregor von Laszewski, Cloudmesh StopWatch and Benchmark from the Cloudmesh Common Library, [GitHub] 
      <https://github.com/cloudmesh/cloudmesh-common>,      <https://www.frontiersin.org/articles/10.3389/fmars.2020.00429/full>

[^4]:  Ulucan, D. Karakaya, M. Turkan Department of Electrical and Electronics Engineering, Izmir University of Economics, Izmir, Turkey Corresponding author: M. Turkan, [Online Resource]  <https://www.kaggle.com/crowww/a-large-scale-fish-dataset>

[^5]:  Campbell, M. D., Salisbury, J., Caillouet, R., Driggers, W. B., and Kilfoil, J. (2018). Camera field-of-view and fish abundance estimation: A comparison of individual-          based model output and empirical data. J./ Exp. Mar. Biol. Ecol. 501, 46–53. [Online resource]

[^6]: Vanni MJ. Annu Rev Ecol Syst. 2002;33:341–370 [Online Resource] <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1838623/>

