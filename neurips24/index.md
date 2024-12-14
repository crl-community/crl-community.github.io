---
layout: neurips24
title: ""
permalink: /neurips24


speakers:

  # - name: Elias Bareinboim (tentative)
  #   url: https://causalai.net/
  #   aff: Columbia Universit
  #   status: tentative
  #   image: assets/images/elias.jpeg

  # - name: Frederick Eberhardt
  #   url: https://www.its.caltech.edu/~fehardt/
  #   aff: California Institute of Technology
  #   status: confirmed
  #   image: assets/images/frederick.jpg
    
  - name: Arthur Gretton
    url: https://www.gatsby.ucl.ac.uk/~gretton/
    aff: Gatsby Computational Neuroscience Unit / UCL / Google Deepmind
    status: confirmed
    image: assets/images/arthur.png

  - name: Yan Liu
    url: https://sites.google.com/view/yanliu-ai/home
    aff: University of Southern California
    status: confirmed
    image: assets/images/YanLiu.png 
  
  - name: Bernhard Schölkopf
    url: https://is.mpg.de/~bs
    aff: Max Planck Institute for Intelligent Systems
    status: confirmed
    image: assets/images/bernhard.jpg
    
  - name: Ilya Shpitser 
    url: https://engineering.jhu.edu/faculty/ilya-shpitser/
    aff: Johns Hopkins University
    status: tentative
    image: assets/images/Ilya.jpg
    
  - name: Caroline Uhler 
    url: https://www.carolineuhler.com/
    aff: Massachusetts Institute of Technology
    status: tentative
    image: assets/images/Uhler.webp
    
  - name: Cheng Zhang
    url: https://cheng-zhang.org/
    aff: Microsoft Research
    status: confirmed speaker only
    image: assets/images/cheng.jpg

Panelist:

  - name: Mingming Gong
    url: https://mingming-gong.github.io/
    topic: 
    aff: University of Melbourne / MBZUAI
    interest: 
    status: confirmed
    image: assets/images/Mingming.jpg
    
  # - name: Emre Kıcıman
  #   url: https://kiciman.org/
  #   aff: Microsoft Research
  #   status: confirmed panelist
  #   image: assets/images/emre.jpg
    
  - name: Jing Ma 
    url: https://jma712.github.io/
    aff: Case Western Reserve University
    status: confirmed panelist
    image: assets/images/jing.jpeg

  - name: Ricardo Silva
    url: https://www.ucl.ac.uk/statistics/people/ricardosilva
    aff: University College London
    status: confirmed panelist only
    image: assets/images/ricardo.jpg
    
  - name: Mihaela van der Schaar
    url: https://www.vanderschaar-lab.com/
    topic: 
    aff: University of Cambridge
    interest: 
    status: confirmed
    image: assets/images/mihaela.png
    
  # - name: Julius von Kügelgen
  #   url: https://www.juliusvonkugelgen.com/
  #   topic: 
  #   aff: ETH Zürich
  #   interest: 
  #   status: confirmed
  #   image: assets/images/julius.jpg
  
  # - name: Luigi Gresele
  #   url: https://lgresele.github.io/
  #   topic: 
  #   aff: University of Copenhagen
  #   interest: 
  #   status: confirmed
  #   image: assets/images/luigi.jpg
  
  
  # - name: James M. Robins (tentative)
  #   url: https://www.hsph.harvard.edu/profile/james-m-robins/
  #   aff: Harvard University
  #   status: tentative
  #   image: assets/images/Robins.jpeg




# OtherStudentOrganizers:


Organizers:

  # - name: Mingming Gong
  #   url: https://mingming-gong.github.io/
  #   # aff: The University of Melbourne / Mohamed bin Zayed University of Artificial Intelligence
  #   aff: The University of Melbourne / MBZUAI
  #   image: assets/images/Mingming.jpg

  - name: Guangyi Chen
    url: https://chengy12.github.io
    # aff: Carnegie Mellon University / Mohamed bin Zayed University of Artificial Intelligence
    aff: Carnegie Mellon University / MBZUAI
    image: assets/images/cgy.jpg
    
  - name: Haoxuan Li
    url: https://scholar.google.com/citations?user=gtDqiucAAAAJ&hl=e
    aff: Peking University
    image: assets/images/haoxuan.jpg

  - name: Sara Magliacane
    url: https://saramagliacane.github.io/
    aff: University of Amsterdam
    image: assets/images/sara.jpg

  - name: Zhijing Jin
    url: https://zhijing-jin.com/fantasy/
    aff: Max Planck Institute / ETH
    image: assets/images/zhijing.png

  - name: Biwei Huang
    url: https://biweihuang.com/
    aff: UC San Diego
    image: assets/images/biwei.png 

  - name: Francesco Locatello
    url: https://www.francescolocatello.com/
    aff: Institute of Science and Technology Austria
    image: assets/images/francesco.jpeg

  - name: Peter Spirtes
    url: https://www.cmu.edu/dietrich/philosophy/people/faculty/spirtes.html
    aff: Carnegie Mellon University
    image: assets/images/peter.jpg

  - name: Kun Zhang
    url: https://www.andrew.cmu.edu/user/kunz1/
    aff: Carnegie Mellon University / MBZUAI
    image: assets/images/kun.jpg





---

# About

Advanced Artificial Intelligence (AI) techniques based on deep representations, such as GPT and Stable Diffusion, have demonstrated exceptional capabilities in analyzing vast amounts of data and generating coherent responses from unstructured data. They achieve this through sophisticated architectures that capture subtle relationships and dependencies. However, these models predominantly identify dependencies rather than establishing and making use of causal relationships. This can lead to potential spurious correlations and algorithmic bias, limiting the models’ interpretability and trustworthiness.
In contrast, traditional causal discovery methods aim to identify causal relationships within observed data in an unsupervised manner. While these methods show promising results in scenarios with fully observed data, they struggle to handle complex real-world situations where causal effects occur in latent spaces when handling images, videos, and possibly text.

Recently, causal representation learning (CRL) has made significant progress in addressing the aforementioned challenges, demonstrating great potential in understanding the causal relationships underlying observed data. These techniques are expected to enable researchers to identify latent causal variables and discern the relationships among them,  which provides an efficient way to disentangle representations and enhance the reliability and interpretability of models.
The goal of this workshop is to explore the challenges and opportunities in this field, discuss recent progress, and identify open questions, and provide a platform to inpire cross-disciplinary collaborations. This workshop will cover both theoretical and applied aspects of CRL, including, but not limited to, the following topics:

- **Theory of causal representation learning**

- **Causal representation learning models**

- **Causal discovery with latent variables**

- **Causal generative models**

- **Causal Foundation Models**

- **Applications of causal representation learning, such as in biology, economics, image/video analysis, and LLMs**

- **Benchmarking causal representation learning**


# Invited Speakers (Ranked by the last name)

{% include team.html id="speakers" %}

# Panelists (Ranked by the last name)

{% include team.html id="Panelist" %} 


<!-- # Open Catalyst Challenge -->

<!-- The Open Catalyst Challenge 2023 invites participants to help address the pressing challenges faced by the world due to energy scarcity and climate change. In this area, a critical problem is the discovery of new catalysts for driving efficient and carbon-neutral means for energy storage and conversion.

Over the past two years, the Open Catalyst Challenge has focused on the central task of relaxed (local minimum) energy prediction. This year’s task of determining the adsorption energy (global minimum) will require relaxed energy prediction as a subtask. -->


<!-- {% include team.html id="opencatalyst" %} -->


# Schedule

- **8:40-8:45 AM:** Welcome remarks
- **8:45-9:15 AM:** Invited Talk 1 by Arthur Gretton (Title: Learning to Act in Noisy Contexts Using Deep Proxy Learning)
- **9:15-9:45 AM:** Invited Talk 2 by Bernhard Schölkopf (Title: What Is a Causal Representation?)
- **9:45-10:00 AM:** Coffee Break
- **10:00-10:30 AM:** Invited Talk 3 by Cheng Zhang (Title: Towards Causal Foundation Model)
- **10:30-10:45 AM:** Contributed Talk 1 (Title: On Domain Generalization Datasets as Proxy Benchmarks for Causal Representation Learning)
- **10:45-11:00 AM:** Contributed Talk 2 (Title: Uncovering Latent Causal Structures from Spatiotemporal Data)
- **11:00-12:00 PM:** Poster Session
- **12:00-2:00 PM:** Lunch Break
- **2:00-2:30 PM:** Invited Talk 4 by Caroline Uhler (Title: TBA)
- **2:30-3:00 PM:** Invited Talk 5 by Yan Li (Title: Frontiers of Counterfactual Outcome Estimation in Time Series )
- **3:00-3:30 PM:** Coffee Break
- **3:30-4:00 PM:** Invited Talk 6 by Ilya Shpitser (Title: Missing Data with ? and 0 Missingness Tokens: Identification and Estimation)
- **4:00-4:15 PM:** Contributed Talk 3 (Title: A Shadow Variable Approach to Causal Decision Making with One-sided Feedback)
- **4:15-4:30 PM:** Contributed Talk 4 (Title: Uncertainty-Aware Optimal Treatment Selection for Clinical Time Series)
- **4:30-5:20 PM:** Panel Discussion
- **5:20-5:30 PM:** Closing Remarks


# Important Dates (Anywhere on Earth,TBD)


- Workshop Papers Submission: ~~September 10, 2024~~ October 2, 2024 (Welcome your ICLR submissions!)
- Acceptance Notification: October 9, 2024
- Camera-ready Deadline and Copyright Form: October 23, 2024
- Workshop Date: December 15, 2024



<!-- # Submissions

Please submit your paper in Openreview. Our workshop is **nonarchival**, the accepted papers will be posted on our website.  -->


<!-- # Organizers and Contact -->

<!-- Organizers are in alphabetical order. For any question, please contact [ai4sciencecommunity@gmail.com](mailto:ai4sciencecommunity@gmail.com). -->


# Organizers:

{% include team.html id="Organizers" %}

For any question, please contact [thecrlcommunity@gmail.com](mailto:thecrlcommunity@gmail.com).

<!-- <ul>
{% for p in page.StudentOrganizers %}
<li>
<a{% if p.url %} href="{{ p.url }}"{% endif %}>{{ p.name }}</a>
</li>
{% endfor %}
</ul>



<ul>
{% for p in page.ProfessorOrganizers %}
<li>
<a{% if p.url %} href="{{ p.url }}"{% endif %}>{{ p.name }}</a>
</li>
{% endfor %}
</ul> -->


<!-- ## CRL Team 

<ul>
{% for p in page.OtherStudentOrganizers %}
<li>
<a{% if p.url %} href="{{ p.url }}"{% endif %}>{{ p.name }}</a>
</li>
{% endfor %}
</ul> -->






