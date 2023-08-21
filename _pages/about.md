---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# About me

I am a PhD student at [Sydney Artificial Intelligence Centre](https://www.sydney.edu.au/engineering/our-research/data-science-and-computer-engineering/ubtech-sydney-artificial-intelligence-centre.html), University of Sydney, supervised by [Prof. Tongliang Liu](https://tongliang-liu.github.io). 

I have always been fascinated by the quest to understand the interpretability of artificial neural networks and the human brain. Lately, my primary focus has been on "Generalization in Deep Learning within Constrained Environments."

# Model Ethology

I propose that we consider deep neural networks entirely as a black-box, and from this perspective, investigate their generalization capabilities. Drawing inspiration from animal ethology, I coined this approach "Model Ethology."

Here are some topics in Model Ethology:

- **Constrained Environments**: By designing limited or "constrained" environments, we can observe how DNNs adapt or falter. For instance, how does a DNN behave when exposed to extremely noisy data, or when its architecture undergoes pruning?
  
- **Instinct vs. Learned Behavior**: In ethology, behaviors are categorized as instinctual or learned. Similarly, for DNNs, we can delve into the difference between behaviors resulting from inherent architectural biases versus those acquired from data.

- **Social Learning**: Just as many animals acquire knowledge through social interactions, how do DNNs learn from other DNNs? Delving into this can provide insights into transfer learning, where one model's expertise is imparted to another.

- **Observable Traits**: Ethologists observe specific traits or behaviors in animals. Analogously, in DNNs, these can manifest as activation patterns in particular layers, or saliency maps highlighting which segments of the input the network deems most informative.

- **Evolutionary Perspectives**: Drawing inspiration from evolutionary practices in ethology, we can study the evolution of DNN architectures throughout the training phase using tools like neural architecture search. Particularly captivating is techniques that introduce randomness during model training, such as Dropout, resonate with the classic Neutral theory of molecular evolution.

In conclusion, by forgoing the need to explicitly interpret the purpose of every neuron and the detailed mathematical and coding interpret of "interpretability" and "generalization theory", and instead observing the network as a holistic organism in diverse scenarios, we might unearth some interesting fact into the realm of deep learning.

I am very much looking forward to any communication on this research methodology, please feel free to share your thoughts!

# Publications and Preprints
- Late Stopping: Avoiding Confidently Learning from Mislabeled Examples.

  **S. Yuan**, L. Feng, and T. Liu. In [ICCV](https://iccv2023.thecvf.com), 2023. [\[PDF\]](https://suqinyuan.github.io)

# Honors and Awards
- *2020.10* China Youth Science and Technology Innovation Award. 
- *2020.05* Chongqing University Youth May·Fourth Medal.  
- *2017.06* China High Shcool Biology Olympiad, first prize (Ranked 12th out of 3,000+ entrants). 

# Educations
- *2022.09 - now*, PhD student, School of Computer Science, University of Sydney. 
- *2018.09 - 2022.06*, Undergraduate, School of Computer Science, Chongqing University. 

# Invited Talks
- *2019.09*, The 4th Global Grand Challenges Summit, Royal Academy of Engineering, London. Oral Presentation, research on bionic robot.  

# Internships
- *2019.07 - 2019.08*, Research Intern, City University of HongKong. 

