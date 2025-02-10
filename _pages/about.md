---
layout: archive
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
    
---
<div class="about-content">
  <p>Hello, I am <strong>Jefferson Rodríguez</strong>, a Ph.D. student in Electronic and Computer Engineering at the <a href="https://www.saiferlab.ai/labs/pralab" target="_blank">PRA Lab</a>, University of Cagliari, Italy. My research focuses on the development of advanced deep learning methodologies applied to biometrics and digital security. I am currently engaged in an innovative doctoral project that investigates the integration of watermarking and steganography techniques for facial images, aiming to improve secure facial image verification, authentication and proactive Deepfake detection.</p>
</div>

<div class="research-interests">
  <h3>Research Interests</h3>
  <ul>
    <li><strong>Biometrics and Digital Security:</strong> Developing secure, resilient authentication/verification systems using state-of-the-art techniques based on biometric data.</li>
    <li><strong>Deep Learning and Image Processing:</strong> Applying neural networks and advanced algorithms to extract and analyze biometric features effectively.</li>
    <li><strong>Watermarking and Steganography:</strong> Innovating methods for embedding and concealing information within facial images to enhance data integrity and security.</li>
    <li><strong>Fraud Detection Systems:</strong> Designing and implementing robust systems for detecting and preventing fraudulent activities within digital environments.</li>
    <li><strong>Model Explainability:</strong> Investigating methods to improve the interpretability and transparency of deep learning models, ensuring that complex algorithms can be understood and trusted by end users.</li>
  </ul>
</div>

---
### Latest News

{% assign news_posts = site.posts | where:"tags","news" | sort:"date" | reverse %}
{% if news_posts.size > 0 %}
<ul class="news-list">
  {% for post in news_posts %}
  <li class="news-item">
    <span class="news-date">{{ post.date | date: "%b %d, %Y" }}</span>
    <a class="news-title" href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
{% else %}
<p>No news available at the moment. Please check back later.</p>
{% endif %}

---
### Publications at a glance

<details>
<summary><strong>Cybersecurity publications</strong></summary>
<ul>
  <li><font size="3">Currently working on Steganography & Watermarking ... </font></li>
  <li><font size="3">Currently working on Behavioral biometrics ... </font></li>
</ul> 
</details>

<details>
<summary><strong>Biomedical imaging publications</strong></summary>
  <ul>
    <li><font size="3">Kinematic motion representation in Cine-MRI to support cardiac disease classification, TCIV, 2022.</font></li>
    <li><font size="3">Deep learning representations to support COVID-19 diagnosis on CT-slices, Biomédica, 2021.</font></li>
    <li><font size="3">A Covid-19 Patient Severity Stratification using a 3D Convolutional Strategy on CT-Scans, ISBI, 2021.</font></li>
    <li><font size="3">Regional multiscale motion representation for cardiac disease prediction, STSIVA, 2019.</font></li>
  </ul>   
</details>

<details>
<summary><strong>Vision-language publications: Sign language recognition </strong></summary>
<ul>
    <li><font size="3">How important is motion in sign language translation?, IET Computer Vision, 2021.</font></li> 
    <li><font size="3">Understanding Motion in Sign Language: A New Structured Translation Dataset, ACCV, 2020.</font></li>  
    <li><font size="3">Towards on-line sign language recognition using cumulative SD-VLAD descriptors, CCC, 2018.</font></li>
    <li><font size="3">A kinematic gesture representation based on shape difference VLAD for sign language recognition, ICCVG, 2018.</font></li>
</ul> 
</details>
