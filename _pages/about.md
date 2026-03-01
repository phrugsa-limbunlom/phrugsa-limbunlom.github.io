---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div class="about-modern" markdown="1">

<p style="font-size: 15px; text-align: justify; margin: 0;">
   I am Phrugsa (Pruk-sa). I am particularly interested in how intelligent systems can learn, reason, and generalise beyond limited training data and small supervision. My work sits at the intersection of machine learning research and real-world system design, with an emphasis on building AI that is both principled and deployable.
<br><br>
  I hold an MSc in Artificial Intelligence from the University of Essex, where I worked on predictive modelling, generative modelling, and large language models. My research interests include generative models, AI agents, and robotics, with a particular focus on reasoning, generalisation, and System-2 thinking. I am currently exploring Joint Embedding Predictive Architectures (JEPA) and Energy-Based Models (EBMs) as methodologies to move beyond purely data-hungry approaches and toward more robust, adaptable, and compositional learning.
<br><br>
  Before and alongside my research work, I gained industry experience as a software engineer and quality engineer, working within Agile development frameworks to design and maintain scalable systems based on microservices and API architectures, while ensuring reliability through both automated and manual testing. This background informs my research perspective to value not only theoretical possibility but also the implementability, empirical evaluation, and long-term sustainability of proposed methods in real-world settings.
<br><br>
  I currently work as an Analyst Developer at the University of Bedfordshire, where I contribute to AI-driven cloud systems that support the digital transformation of enterprise platforms. My role involves integrating modern AI methods with cloud infrastructure to improve efficiency and decision-making at scale.
<br><br>
  In parallel, I am an open-source contributor, a freelancer helping start-ups leverage AI capabilities in their products and workflows, and a technical writer publishing in-depth articles for leading AI publications on Medium. I enjoy translating complex ideas into clear explanations without losing technical depth. I am open to research collaborations, particularly on projects with meaningful societal impact.
</p>


Research Interest
-------------------------------------
<p style="font-size: 15px; text-align: justify; margin: 0;">
    My research interest focuses on enhancing cognitive functions in current machine intelligence systems. This interest was motivated by my previous work, where I observed that models often struggle with requiring vast amounts of data for training and fail to generalize to unseen data that deviates from the training distribution (out-of-distribution generalization). After reading the paper,  <a href="https://openreview.net/pdf?id=BZ5a1r-kVsf" style="font-style: italic;"> A Path Towards Autonomous Machine Intelligence </a>, by Yann LeCun, I realized that these issues stem from a lack of reasoning in current models, which need further improvement in their cognitive mechanisms. I am particularly interested in researching approaches to tackle reasoning challenges in large language models (LLMs) and multimodal systems, especially in vision-related tasks. I am currently exploring the feasibility of leveraging Joint-Embedding Predictive Architecture (JEPA) and energy-based models to address these problems. My goal is to develop an intelligent system that requires a small sample for training to learn new situations.
</p>

Previous Research
--------------------------------------

<details class="about-collapsible">
<summary>SE-GAN: Sentiment-Enhanced GAN for Stock Price Forecasting</summary>
<br>
<p style="text-align: center">
    <a href="https://github.com/phrugsa-limbunlom/SeGAN">(SeGAN)</a>
</p>
<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/5a83d6f7-6225-42f2-a544-a17449c91299" width="600" height="450">
</div>
<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/aac2418c-0540-425e-9e1e-f666e4475cbe" width="600" height="450">
</div>
<br>
<div style="text-align: center">
    Abstract
</div>
<br>
<p style="font-size: 15px; text-align: justify; margin: 0;">
    Stock price prediction is a challenging task due to the inherent volatility of the market and the complexity of price movement. Traditional models still encounter limitations when faced with restricted historical data, which leads to over-fitting problems and poor performance on unseen data. Furthermore, market sentiment is a crucial factor for price fluctuations, yet several models still fail to adequately capture this important factor. To address the issues, the research proposes a novel deep learning network architecture. The approach leverages generative adversarial networks (GANs) to expand the training set and generalize on unseen data by generating synthetic historical data. As the GAN model generates prediction of closing prices, the generated prices can be compared with actual market movements to assess its performance. To capture the impact of market sentiment, the model also integrates sentiment analysis from financial news. This integration allows a more comprehensive technique for price forecasting, considering both quantitative historical data and qualitative sentiment indicators. The model was trained on historical data of Microsoft stock (MSFT) from January 2013 to December 2023. To conduct market sentiment analysis on financial news, FINBERT will be utilized to extract sentiment scores from headlines. Additionally, various index of Microsoft stock (MSFT) are integrated in the training data. The proposed model, Sentiment-Enhanced GAN (SE-GAN), integrates sentiment analysis with generative adversarial networks (GANs) to generate more robust and accurate stock price predictions. The SE-GAN model demonstrates the lowest Root Mean Square Error(RMSE) for overall experiment setting compared to baselines models including Long Short- Term Memory (LSTM) and Gated Recurrent Unit (GRU), as well as TimeGPT as another generative model. The improvement suggests that the SE-GAN approach offers a more effective method for predicting stock prices, leveraging the combined strengths of sentiment analysis and generative adversarial networks (GANs).
</p>
<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/801ac480-1371-453a-9fc5-f7a823f136ec">
</div>
<br>
<p style="font-size: 15px; text-align: justify; margin: 0;">
    <strong>Keywords</strong>: Stock Price Prediction, Sentiment Analysis, Generative Adversarial Networks (GANs), FINBERT
</p>
</details>

<details class="about-collapsible">
<summary>MANDY: Empirical Investigation And Supporting Program For Mandibular Fracture Classification And Localization Algorithms On X-ray Images Of Skulls</summary>
<br>
<p style="text-align: center">
    <a href="https://github.com/phrugsa-limbunlom/GradCAM/tree/master">(GradCAM)</a>
</p>
<br>
<div style="text-align: center;">
    <img src="../Mandy.png" width="600" height="450">
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
</details>

Paper
--------------------------------------
<div class="about-card-grid about-card-grid--single">
    <a href="https://doi.org/10.36227/techrxiv.175742717.74182135/v1" class="about-card-link" target="_blank" rel="noopener">
    <article class="about-card about-card--paper">
        <img class="about-card__img" src="/images/paper_sequential.jpg" alt="Sequential input and output prediction">
        <div class="about-card__body">
            <span class="about-card__tag about-card__tag--paper">Preprint</span>
            <h3>Deep Adversarial Learning for Financial Time-Series Forecasting (SE-GAN)</h3>
            <p>P. Limbunlom, TechRxiv, Sep. 9, 2025</p>
        </div>
    </article>
    </a>
</div>

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
<li> AWS Certified: Machine Learning Engineer Associate (MLA-C01)</li>
<li> Microsoft Certified: Azure AI Engineer Associate (AI-102)</li>
<li> IBM Generative AI Engineering with LLM Specialization </li>
<li> NVIDIA AI Infrastructure and Operations Fundamentals </li>
<li> Deep Learning Specialization</li>
<li> AWS Cloud Practitioner</li>
</ul>

<div style="text-align: center;">
    <a href="https://www.credly.com/badges/3c9d4fda-e1e2-4bf1-b0a5-1fcf91ca3d71"><img src="/images/AWS-ML.png" width="100" height="100"></a>
    <a href="https://www.credly.com/badges/aec100a4-3112-4f1b-9616-0eac251071d6"><img src="/images/AWS-CLOUD.png" width="100" height="100"></a>
    <a href="https://learn.microsoft.com/en-us/users/phrugsalimbunlom-0283/credentials/4e89a1228e27e99d"><img src="/images/Azure-AI.png" width="100" height="100"></a>
</div>

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

</div>