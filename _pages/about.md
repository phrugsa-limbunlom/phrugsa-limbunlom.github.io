---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p style="font-size: 15px; text-align: justify; margin: 0;">
    I am passionate to apply my skills in AI, software engineering, and QA to design efficient and reliable intelligence systems. Before starting my master’s program, I worked as a software engineer building robust and scalable software through microservices and API integration. I also gained experience as a quality engineer conducting both manual and automated testing to maintain rigorous software quality. My career has included roles at global IT consulting firms, where I contributed to Agile projects and collaborated with cross-functional teams. With a solid foundation in both software development and quality assurance, I am now eager to deepen my expertise in AI. After completing my master’s degree, I look forward to utilizing my expertise to create cutting-edge AI-powered solutions and advancing my research capabilities in Cognitive AI and AI reasoning.
</p>
<br>

<!--<div style="display: flex; gap: 20px; justify-content: center; align-items: center;">
<a href="https://github.com/phrugsa-limbunlom" target="_blank" rel="noopener noreferrer">
            <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub" width="30" height="30">
</a> -->

<!-- <a href="https://www.linkedin.com/in/phrugsa-limbunlom-5b8995117/" target="_blank" rel="noopener noreferrer">
    <img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="LinkedIn" width="30" height="30">
</a>

<a href="https://phrugsa-limbunlom.medium.com/" target="_blank" rel="noopener noreferrer">
    <img src="https://cdn-icons-png.flaticon.com/512/5968/5968906.png" alt="Medium" width="30" height="30">
</a>
</div> -->

Industry-based Project Interest
-------------------------------------
<p style="font-size: 15px; text-align: justify; margin: 0;">
    My industry-based project interest aligns with developing AI-driven software solutions to address business challenges and drive growth. My primary focus is creating software that seamlessly integrates Generative and Agentic AI to optimize and enhance business processes. I also aim to develop user-friendly software that can solve real-world challenges and make it more convenient for users without a technical background. 
</p>
<p style="font-size: 15px; text-align: justify; margin: 0;">One project example is <a href="https://github.com/phrugsa-limbunlom/PickSmart">PickSmart</a>, an AI-powered shopping assistant combining real-time product search with contextual question-answering for  personalized product recommendations using the search and analyst agent.</p>
<br>
<div style="text-align: center">
    <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7299436712282255360" height="300" width="360" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
</div>

Research Interest
-------------------------------------
<p style="font-size: 15px; text-align: justify; margin: 0;">
    My research interest focuses on enhancing cognitive functions in current machine intelligence systems. This interest was motivated by my previous work, where I observed that models often struggle with requiring vast amounts of data for training and fail to generalize to unseen data that deviates from the training distribution (out-of-distribution generalization). After reading the paper,  <a href="https://openreview.net/pdf?id=BZ5a1r-kVsf" style="font-style: italic;"> A Path Towards Autonomous Machine Intelligence </a>, by Yann LeCun, I realized that these issues stem from a lack of reasoning in current models, which need further improvement in their cognitive mechanisms. I am particularly interested in researching approaches to tackle reasoning challenges in large language models (LLMs) and multimodal systems, especially in vision-related tasks. I am currently exploring the feasibility of leveraging Joint-Embedding Predictive Architecture (JEPA) and energy-based models to address these problems. My goal is to develop an intelligent system that requires a small sample for training to learn new situations.
</p>

Previous Research
--------------------------------------
<br>
<div style="text-align: center; font-weight: bold;">
    SE-GAN: Sentiment-Enhanced GAN for Stock Price Forecasting
</div>
<p style="text-align: center">
    <a href="https://github.com/phrugsa-limbunlom/SeGAN">(SeGAN)</a>
</p>
<br>
<div style="text-align: center">
    Abstract
</div>
<br>
<p style="font-size: 15px; text-align: justify; margin: 0;">
    Stock price prediction is a challenging task due to the inherent volatility of the market and the complexity of price movement. Traditional models still encounter limitations when faced with restricted historical data, which leads to over-fitting problems and poor performance on unseen data. Furthermore, market sentiment is a crucial factor for price fluctuations, yet several models still fail to adequately capture this important factor. To address the issues, the research proposes a novel deep learning network architecture. The approach leverages generative adversarial networks (GANs) to expand the training set and generalize on unseen data by generating synthetic historical data. As the GAN model generates prediction of closing prices, the generated prices can be compared with actual market movements to assess its performance. To capture the impact of market sentiment, the model also integrates sentiment analysis from financial news. This integration allows a more comprehensive technique for price forecasting, considering both quantitative historical data and qualitative sentiment indicators. The model was trained on historical data of Microsoft stock (MSFT) from January 2013 to December 2023. To conduct market sentiment analysis on financial news, FINBERT will be utilized to extract sentiment scores from headlines. Additionally, various index of Microsoft stock (MSFT) are integrated in the training data. The proposed model, Sentiment-Enhanced GAN (SE-GAN), integrates sentiment analysis with generative adversarial networks (GANs) to generate more robust and accurate stock price predictions. The SE-GAN model demonstrates the lowest Root Mean Square Error(RMSE) for overall experiment setting compared to baselines models including Long Short- Term Memory (LSTM) and Gated Recurrent Unit (GRU), as well as TimeGPT as another generative model. The improvement suggests that the SE-GAN approach offers a more effective method for predicting stock prices, leveraging the combined strengths of sentiment analysis and generative adversarial networks (GANs).
</p>
<br>
<p style="font-size: 15px; text-align: justify; margin: 0;">
    <strong>Keywords</strong>: Stock Price Prediction, Sentiment Analysis, Generative Adversarial Networks (GANs), FINBERT
</p>
<br>
<br>
<div style="text-align: center; font-weight: bold;">
    MANDY: Empirical Investigation And Supporting Program For Mandibular Fracture Classification And Localization Algorithms On X-ray Images Of Skulls
</div>
<br>
<div style="text-align: center">
    Abstract
</div>
<br>
<p style="font-size: 15px; text-align: justify; margin: 0;">
Traffic accidents are a serious situation in Thailand. These accidents are prevalent and lead to a number of patients encountering fractures on their facial skulls. The mandible is a prominent bone in the face that is relatively easy to break, and although treatment can be effective, doctors need to know the fracture locations immediately to reduce the risk of other injuries. Diagnoses of the fractures is normally done by X-Ray due to its inexpensive cost. However, locating fractures in the mandible using X-Ray film can be difficult and often requires the opinion of  specialists. As such, a computer-aided diagnostic tool would lead to faster, more accurate, and less costly analysis. To our knowledge, no research has been undertaken on the effectiveness of such technology in mandibular fracture detection from X-Ray images. This research aims to investigate relevant models for images classification using convolutional neural networks (CNNs) and transferring techniques from pre-trained models to identify the names of mandibular fracture, also employ Gradient-weighted Class Activation Mapping (GradCAM) to localize the location of those fractures on x-ray images. Moreover, the trained model was deployed to create a diagnostic system helping non-specialist doctors diagnose mandibular fractures more accurately and efficiently without requiring a reference to specialists, as well as support medical research to study the effectiveness of web applications in clinical practice.
</p>
<br>

<div style="text-align: center;">
    <video width="360" height="180" controls>
    <source src="Mandy.mp4" type="video/mp4">
    </video>
</div>
<br>

<p style="font-size: 15px; text-align: justify; margin: 0;">
    <strong>Keywords:</strong> Convolutional Neural Network, GradCAM, Mandibular Fracture, Classification, Localization, X-ray Image
</p>

Blog Post
--------------------------------------
<ul style="font-size: 15px;">
    <li><a  href="https://phrugsa-limbunlom.medium.com/what-you-may-miss-about-the-core-concept-of-the-gan-model-f1820d3f7efc">What you may miss about the core concept of the GAN model</a></li>
    <li><a  href="https://phrugsa-limbunlom.medium.com/key-takeaways-ai-infrastructure-and-operations-fundamental-by-nvidia-ea7742f0e348">Key Takeaways: AI Infrastructure and Operations Fundamental by NVIDIA.</a></li>
</ul>

Education
--------------------------------------
<p style="font-size: 15px;">
    MSc, Artificial Intelligence and its Applications, CSEE, University of Essex (Distinction)
</p>
<p style="font-size: 15px;">
    BSc, Major Computer Science, Faculty of ICT, Mahidol University (3.62/4.00)
</p>
<p style="font-size: 15px;">
    Certificate of Completion, Artificial Intelligence (87%), ISS 2019, Sungkyunkwan University
</p>

Certificates
---------------------------------------
<ul style="font-size: 15px;">
<li> Microsoft Certified: Azure AI Engineer Associate (AI-102)</li>
<li> NVIDIA AI Infrastructure and Operations Fundamentals </li>
<li> Deep Learning Specialization</li>
<li> AWS Cloud Practitioner</li>
<li> IBM Generative AI Engineering with LLM Specialization </li>
</ul>

Awards
---------------------------------------
<ul style="font-size: 15px;">
    <li>Academic Excellence International Master Scholarship from University of Essex</li>
    <li>The Big Essex Bronze Award 2024 from University of Essex</li>
    <li>Winner Award for Outstanding Innovation in <i> Free smoking university project 2019 </i> issued by The Medical Association of Thailand from <i><a href="https://github.com/phrugsa-limbunlom/Cigarless/tree/main"> CIGARLESS </a> </i> application</li>
</ul>

More About Me
----------------------------------------
<p style="font-size: 15px; text-align: justify; margin: 0;">
    I am passionate about cutting-edge technology and fascinated by how the industry drives core development while leveraging its capabilities to create applications serving real users effectively.
    Apart from technology, I like science, evolution, and history. Visiting museum is my another hobby.
</p>
<br>
<div style="text-align: center;">
<img src="/images/image1.jpg" alt="Description" style="border-radius: 50%; width: 100px; height: 100px;">
<img src="/images/image3.jpg" alt="Description" style="border-radius: 50%; width: 100px; height: 100px;">
<img src="/images/image2.jpg" alt="Description" style="border-radius: 50%; width: 100px; height: 100px;">
</div>