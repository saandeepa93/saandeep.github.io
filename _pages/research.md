---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My philosphy of research in deep learning (and sometimes ML) is to reduce/remove its black box nature.
The output of my research work has potential applications in Healthcare and Biometrics. Therefore, 
the need for explainability is of paramount importance.

# **Affective Computing**
Considering this, my PhD thesis is two-fold: Modelling the complex affect data by combining representation learning
techniques and Flow-based generative models, and developing new methods to predict/classify 
different affective components. Currently, the existing work is limited to structured modalities like images but I intend to extend it to unstructured data like continuous signals and tabular data.

# **Healthcare**
I am also working on a collaborative project with the Social Behaviour department at USF to develop techniques for automatic recognition of PTSD in children. This study include using computer vision tools such as [Openface](https://github.com/TadasBaltrusaitis/OpenFace) to analyze videos of participants with potential trauma interacting with a psychiatrist and develop an algorithm to succesfully predict PTSD. The primary work is to explain why the ML/DL model thinks a participant does or does not have PTSD.

# **Biometrics**
A new venue in my research includes a collaborative work under NSF wherein *continuous authentication (CA)* on mobile devices using unstructured modalities like physiological signals, EEG etc. Plenty of importance is given to practical implementation of CA considering the ethical aspects of the data being collected. 



<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

<!-- {% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %} -->
