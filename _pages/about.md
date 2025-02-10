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
Hello, I am **Jefferson Rodríguez**, a Ph.D. student in Electronic and Computer Engineering at the PRA Lab, University of Cagliari, Italy. My research focuses on the development of advanced deep learning methodologies applied to biometrics and digital security. I am currently engaged in an innovative doctoral project that investigates the integration of watermarking and steganography techniques for facial images, aiming to improve secure facial image verification, authentication and proactive Deepfake detection.

---
### Research Interests

My primary research interests include:
- **Biometrics and Digital Security:** Developing secure, resilient authentication/verification systems using state-of-the-art techniques based on biometric data.
- **Deep Learning and Image Processing:** Applying neural networks and advanced algorithms to extract and analyze biometric features effectively.
- **Watermarking and Steganography:** Innovating methods for embedding and concealing information within facial images to enhance data integrity and security.
- **Fraud Detection Systems:** Designing and implementing robust systems for detecting and preventing fraudulent activities within digital environments.
- **Model Explainability:** Investigating methods to improve the interpretability and transparency of deep learning models, ensuring that complex algorithms can be understood and trusted by end users.

---

## Latest News

{% assign news_posts = site.posts | where:"tags","news" | sort:"date" | reverse %}
{% if news_posts.size > 0 %}
<ul class="news-list">
  {% for post in news_posts %}
  <li class="news-item">
    <span class="news-date">{{ post.date | date: "%b %d, %Y" }}</span>
    <a class="news-title" href="{{ post.url }}">{{ post.title }}</a>
    <p class="news-excerpt">{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
  </li>
  {% endfor %}
</ul>
{% else %}
<p>No news available at the moment. Please check back later.</p>
{% endif %}


---
### Academic and Professional Background

<details>
<summary><strong>Doctoral Research in Biometrics</strong></summary>
  
I am currently engaged in doctoral research that focuses on leveraging advanced deep learning models to enhance biometric security. My work involves developing innovative watermarking and steganographic techniques for facial image authentication/verification, addressing critical challenges in digital fraud prevention and secure identity verification.

</details>

<details>
<summary><strong>Industry Experience in Cybersecurity</strong></summary>
  
My experience as a data scientist at Appgate provided me with invaluable, hands-on experience in the cybersecurity industry. During my time there, I worked on the development of cutting-edge products for fraud detection, biometric authentication, and device recognition. This role not only refined my technical and analytical skills but also offered me a unique perspective on real-world security challenges. It was this experience that inspired and motivated me to further pursue advanced research in cybersecurity, ensuring that my academic work remains deeply connected to industry needs.

</details>

<details>
<summary><strong>Interdisciplinary Expertise in Computer Vision</strong></summary>
  
My academic journey began with an undergraduate focus on video-based sign language recognition, marking my initial foray into computer vision. During my master’s studies, I advanced my expertise by developing methods to translate sign language from video to text using advanced deep learning techniques and vision-language models. Concurrently, I participated in biomedical projects—such as cardiac disease diagnosis and COVID-19 detection from medical images—that sharpened my skills in visual data analysis and pattern recognition.

This diverse academic background has endowed me with a robust and transversal expertise in computer vision, which I now leverage to address complex challenges in cybersecurity and biometric systems. Moreover, my involvement in interdisciplinary projects integrating data analytics, machine learning, and image processing has enabled me to bridge theoretical research with real-world applications through an innovative perspective.

</details>


<details>
<summary><strong>Vision and Future Directions</strong></summary>
  
I am committed to advancing the fields of Cibersecurity & MLSec specially in biometric security through rigorous research and interdisciplinary collaboration. My ambition is to contribute to the development of robust authentication/verification systems capable of addressing emerging challenges in digital security. I strive for academic excellence and the practical application of research findings to create solutions that are both innovative and impactful.

I invite you to explore my research projects and publications, and welcome opportunities for collaboration on topics related to deep learning, biometrics, and cybersecurity.

</details>

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
