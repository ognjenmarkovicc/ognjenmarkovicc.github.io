---
layout: post
title:  "Tracking Serbia COVID-19 cases."
date:   2020-03-15 20:15:38 -0700
categories: COVID-19
tags: [COVID-19, data analysis, plotly]
---

This page is tracking current COVID-19 case data from Serbia/Ova stranica prati trenutni broj COVID-19 slučajeva u Srbiji.


Data was collected manually from [covid19.rs](https://covid19.rs/). 
There are a few inconsistencies with reported daily testing numbers and cumulative testing numbers, so the testing numbers are adjusted to match the reported cumulative number of cases.

{% include Serbia-cases.html %}


Daily testing and confirmed cases:

{% include Serbia-cases-tested-bar.html %}
