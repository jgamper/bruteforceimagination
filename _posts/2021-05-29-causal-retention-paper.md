---
layout: distill
title: "Distilling Uber's Causal Learning for User Retention"
date: 2021-05-29T19:34:30-04:00
description: An attempt to understand and reproduce a paper from Uber Research.

authors:
  - name: Jevgenij Gamper
    url: 
    affiliations:
      name: 

bibliography: 2021-05-29-uber-causal.bib

# Below is an example of injecting additional post-specific styles.
# If you use this post as a template, delete this _styles block.
_styles: >
  .fake-img {
    background: #bbb;
    border: 1px solid rgba(0, 0, 0, 0.1);
    box-shadow: 0 0px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 12px;
  }
  .fake-img p {
    font-family: monospace;
    color: white;
    text-align: left;
    margin: 12px 0;
    text-align: center;
    font-size: 16px;
  }

---

**NOTE:**
Citations, footnotes, and code blocks do not display correctly in the dark mode since distill does not support the dark mode by default.
Click on the sun above to disable dark mode.
---

At first thought, these moments at the intersection of digital 
and physical life may seem unimportant. Yet, most of us had experienced the following 
sequence of events. 

It's weekend, you are at home occupied by your hobby. 
A notification pops up on your phone, making a sound that by now your brain associates 
with either an important email, or a calendar reminder. 

Unless you have notifications completely switched off,  you will discover that it is an 
app reminding you about itself. The kind of app that you have not used in a while. 

What do you do next? Irritated (or not) by the notification you have a few options: 
* Delete the app
* Put the phone down and carry on with your day. 
* It's Dualingo reminding you about your New Years resolution to learn Japanese? 
  You may actually think its a good idea and open the app straight away!

It indeed was Dualingo, and you choose the third option. It managed to convince you 
to put aside your weekend activity 
and spend another hour on the phone. Somewhere, data scientists are raving - one more 
customer retained! 

How did they do that? There are many ways to convince someone to use or to continue 
using the product. But we are not going to talk about the marketing strategies specifics. 
We are going to talk about one of the ways that we can formulate retention as a Data 
Science problem! One possible way is described in
[_Improve User Retention with Causal Learning_ (2019)](http://proceedings.mlr.press/v104/du19a.html) 
by Du et al. from Uber. 

Warning! We do not have access to the data used in their study. That is fine! It is not 
an issue at all. In fact, we are over emphasising the importance of large datasets 
for research success. I hear that we cannot compete with FAANG due to their access to 
gpu-clusters and large datasets. We don't have to! Let's not play the game where they 
set the rules. There are plenty of examples of well designed studies, that lead to 
insights and need far less computational power. With the perk of having fewer degrees 
of freedom to control for. Fewer hyper-paratemers, no parallel computation quirks, etc. 

