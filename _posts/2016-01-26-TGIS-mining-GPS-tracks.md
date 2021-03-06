---
layout: post
title: Automatic Update of Road Attributes by Mining GPS Tracks
categories: news
date: 2016-01-26
---

We have published a new journal paper on mining GPS tracks for inferring road characteristics. Our method can be used to enrich road data sets, such as OpenStreetMap, to enhance its level of completeness.

van Winden, K., Biljecki, F., and van der Spek, S.  (2016). Automatic Update of Road Attributes by Mining GPS Tracks. <i>Transactions in GIS</i>. [doi:10.1111/tgis.12186](http://doi.org/10.1111/tgis.12186)

Abstract: Despite advances in cartography, mapping is still a costly process which involves a substantial amount of manual work. This article presents a method for automatically deriving road attributes by analyzing and mining movement trajectories (e.g. GPS tracks). We have investigated the automatic extraction of eight road attributes: directionality, speed limit, number of lanes, access, average speed, congestion, importance, and geometric offset; and we have developed a supervised classification method (decision tree) to infer them. The extraction of most of these attributes has not been investigated previously. We have implemented our method in a software prototype and we automatically update the OpenStreetMap (OSM) dataset of the Netherlands, increasing its level of completeness. The validation of the classification shows variable levels of accuracy, e.g. whether a road is a one- or a two-way road is classified with an accuracy of 99%, and the accuracy for the speed limit is 69%. When taking into account speed limits that are one step away (e.g. 60 km/h instead of the classified 50 km/h) the classification increases to 95%, which might be acceptable in some use-cases. We mitigate this with a hierarchical code list of attributes.

The freely available author's version PDF is available [here](http://filipbiljecki.com/publications/vanWinden2016ur.pdf). Please use the [publisher's version](http://doi.org/10.1111/tgis.12186) if available to you.

<img src="{{ site.baseurl }}/img/2016/tgis-gps.png"/>