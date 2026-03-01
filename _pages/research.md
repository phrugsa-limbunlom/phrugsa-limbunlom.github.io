---
permalink: /research/
title: "Research"
author_profile: true
---
<div class="about-modern" markdown="1">

Paper
--------------------------------------
<div class="about-card-grid about-card-grid--single">
    <article class="about-card about-card--paper">
        <img class="about-card__img" src="https://github.com/user-attachments/assets/5a83d6f7-6225-42f2-a544-a17449c91299" alt="SE-GAN">
        <div class="about-card__body">
            <span class="about-card__tag about-card__tag--paper">Preprint</span>
            <h3>Deep Adversarial Learning for Financial Time-Series Forecasting (SE-GAN)</h3>
            <p>P. Limbunlom, TechRxiv, Sep. 9, 2025</p>
            <p><a href="https://doi.org/10.36227/techrxiv.175742717.74182135/v1" class="about-card__link">Read paper &rarr;</a></p>
        </div>
    </article>
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
<br>
<br>
<div style="text-align: center; font-weight: bold;">
    MANDY: Empirical Investigation And Supporting Program For Mandibular Fracture Classification And Localization Algorithms On X-ray Images Of Skulls
</div>
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

</div>
