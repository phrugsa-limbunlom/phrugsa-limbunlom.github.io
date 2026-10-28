---
permalink: /
title: "Phrugsa Limbunlom"
layout: academic
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="ac-container">

<header class="ac-header">
  <img class="ac-header__photo" src="/images/profile2.jpeg" alt="Phrugsa Limbunlom">
  <div>
    <h1 class="ac-header__name">Phrugsa Limbunlom</h1>
    <p class="ac-header__title">AI Researcher and Developer</p>
    <p class="ac-header__links">
      <a href="mailto:phrugsa.lim@gmail.com"><i class="fas fa-envelope"></i>Email</a>
      <a href="https://github.com/phrugsa-limbunlom" target="_blank" rel="noopener"><i class="fab fa-github"></i>GitHub</a>
      <a href="https://orcid.org/0009-0004-2356-0710" target="_blank" rel="noopener"><i class="fab fa-orcid"></i>ORCID</a>
      <a href="https://phrugsa-limbunlom.medium.com/" target="_blank" rel="noopener"><i class="fab fa-medium"></i>Medium</a>
      <a href="https://www.linkedin.com/in/phrugsa-limbunlom-5b8995117/" target="_blank" rel="noopener"><i class="fab fa-linkedin"></i>LinkedIn</a>
      <a href="https://twitter.com/PhrugsaL" target="_blank" rel="noopener"><i class="fab fa-twitter"></i>Twitter</a>
    </p>
  </div>
</header>

<blockquote class="ac-quote">
  <p>&ldquo;Imagination is more important than knowledge.&rdquo;</p>
  <cite>Albert Einstein</cite>
</blockquote>

<section class="ac-section ac-prose" id="about">
  <h2>About</h2>
  <p>
    I work on probabilistic generative models (energy-based models, diffusion, and flow matching) and principled sampling methods, and turn them into open-source scientific software. I hold a master's degree in Artificial Intelligence from the University of Essex (UK) and a bachelor's degree in Computer Science from Mahidol University (Thailand).
  </p>
  <p>
    My ultimate goal is to build learning systems that remain data-driven yet are data-efficient by design, generalising well to out-of-distribution data by learning the underlying structure and dynamics of the world rather than relying on large labelled datasets. I am particularly drawn to world models and active inference, where agents learn by predicting their environment and acting to reduce uncertainty.
  </p>
</section>

<section class="ac-section" id="research">
  <h2>Research Interests</h2>
  <ul>
    <li><strong>Medical AI &amp; AI for Science</strong>: high-stakes domains with scarce data and high uncertainty.</li>
    <li><strong>Generative modelling</strong>: energy-based models, diffusion, flow matching.</li>
    <li><strong>Representation learning</strong>: self-supervised, structured and invariant representations.</li>
    <li><strong>World models</strong>: action-conditioned predictive models for planning in representation space.</li>
    <li><strong>Multimodal learning</strong>: unified representations across vision, language, time series and other modalities.</li>
  </ul>
</section>

<section class="ac-section" id="preprint">
  <h2>Preprint</h2>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/paper_sequential.jpg" alt="SE-GAN" loading="lazy">
    <div>
      <p class="ac-entry__title">Deep Adversarial Learning for Financial Time-Series Forecasting (SE-GAN)</p>
      <p class="ac-entry__venue"><span class="ac-me">P. Limbunlom</span> &middot; <em>TechRxiv preprint</em>, 2025</p>
      <p class="ac-entry__desc">Sentiment-conditioned GAN (FinBERT) for stock-price forecasting; lowest RMSE vs. LSTM, GRU and TimeGPT.</p>
      <p class="ac-links">
        <a href="https://doi.org/10.36227/techrxiv.175742717.74182135/v1" target="_blank" rel="noopener">Paper</a>
        <a href="https://github.com/phrugsa-limbunlom/SeGAN" target="_blank" rel="noopener">Code</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/Mandy2.png" alt="MANDY" loading="lazy">
    <div>
      <p class="ac-entry__title">MANDY: Mandibular Fracture Classification &amp; Localization on X-ray Images</p>
      <p class="ac-entry__venue"><span class="ac-me">P. Limbunlom</span> &middot; <em>Thesis</em></p>
      <p class="ac-entry__desc">CNN transfer learning for fracture classification with Grad-CAM localisation.</p>
    </div>
  </div>
</section>

<section class="ac-section" id="software">
  <h2>Open-Source Software</h2>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/visualization/flow.gif" alt="DeltaFlow" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://github.com/phrugsa-limbunlom/deltaflow" target="_blank" rel="noopener">DeltaFlow</a></p>
      <p class="ac-entry__venue">Author &middot; PyTorch</p>
      <p class="ac-entry__desc">Flow matching with anatomy-invariant guidance alignment for radiograph generative pretraining. Domain-agnostic interpolants, samplers and losses.</p>
      <p class="ac-links">
        <a href="https://github.com/phrugsa-limbunlom/deltaflow" target="_blank" rel="noopener">GitHub</a>
        <a href="https://pypi.org/project/torchdeltaflow/" target="_blank" rel="noopener">PyPI</a>
        <a href="https://phrugsa-limbunlom.github.io/deltaflow/" target="_blank" rel="noopener">Docs</a>
        <a class="ac-badge" href="https://pepy.tech/project/torchdeltaflow" target="_blank" rel="noopener" title="Downloads"><img alt="Downloads" src="https://static.pepy.tech/badge/torchdeltaflow?style=flat-square"></a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/visualization/hmc_vs_rmhmc_phase.gif" alt="HMC vs RMHMC" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://github.com/soran-ghaderi/torchebm" target="_blank" rel="noopener">TorchEBM</a></p>
      <p class="ac-entry__venue">Contributor &middot; PyTorch</p>
      <p class="ac-entry__desc">Energy-based modelling library. Contributed HMC and Riemannian-manifold HMC samplers with phase-space visualisations.</p>
      <p class="ac-links">
        <a href="https://github.com/soran-ghaderi/torchebm" target="_blank" rel="noopener">GitHub</a>
        <a href="https://soran-ghaderi.github.io/torchebm/latest/" target="_blank" rel="noopener">Docs</a>
        <a class="ac-badge" href="https://pepy.tech/project/torchebm" target="_blank" rel="noopener" title="Downloads"><img alt="Downloads" src="https://static.pepy.tech/badge/torchebm?style=flat-square"></a>
      </p>
    </div>
  </div>
</section>

<section class="ac-section" id="articles">
  <h2>Technical Articles</h2>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/visualization/flow.gif" alt="Flow matching" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://medium.com/towards-artificial-intelligence/generative-modelling-with-flow-matching-optimal-transport-and-schr%C3%B6dinger-bridge-3bbfe986b4de" target="_blank" rel="noopener">Generative Modelling with Flow Matching, Optimal Transport, and Schrödinger Bridge</a></p>
      <p class="ac-entry__venue"><em>Towards AI</em></p>
      <p class="ac-links">
        <a href="https://medium.com/towards-artificial-intelligence/generative-modelling-with-flow-matching-optimal-transport-and-schr%C3%B6dinger-bridge-3bbfe986b4de" target="_blank" rel="noopener">Article</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/visualization/diffusion_cfg_reverse.gif" alt="Classifier-free guidance" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://pub.towardsai.net/physics-inspired-generative-modeling-diffusion-flow-matching-and-energy-based-models-9cbacb24488a" target="_blank" rel="noopener">Physics-Inspired Generative Modeling: Diffusion, Flow Matching, and Energy-Based Models</a></p>
      <p class="ac-entry__venue"><em>Towards AI</em></p>
      <p class="ac-links">
        <a href="https://pub.towardsai.net/physics-inspired-generative-modeling-diffusion-flow-matching-and-energy-based-models-9cbacb24488a" target="_blank" rel="noopener">Article</a>
        <a href="https://github.com/phrugsa-limbunlom/generative-modelling" target="_blank" rel="noopener">Code</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/medium/Grpo.webp" alt="GRPO" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://medium.com/towards-artificial-intelligence/training-your-reasoning-model-with-grpo-a-practical-guide-for-vlms-post-training-with-trl-266411c0b844" target="_blank" rel="noopener">Training Your Reasoning Model with GRPO: VLM Post-Training with TRL</a></p>
      <p class="ac-entry__venue"><em>Towards AI</em></p>
      <p class="ac-links">
        <a href="https://medium.com/towards-artificial-intelligence/training-your-reasoning-model-with-grpo-a-practical-guide-for-vlms-post-training-with-trl-266411c0b844" target="_blank" rel="noopener">Article</a>
        <a href="https://github.com/phrugsa-limbunlom/vlm-grpo" target="_blank" rel="noopener">Code</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/medium/LoRa.webp" alt="LoRA" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://medium.com/@phrugsa-limbunlom/lora-in-vision-language-models-efficient-fine-tuning-with-llava-c8948674d855" target="_blank" rel="noopener">LoRA in Vision-Language Models: Efficient Fine-Tuning with LLaVA</a></p>
      <p class="ac-entry__venue"><em>Medium</em></p>
      <p class="ac-links">
        <a href="https://medium.com/@phrugsa-limbunlom/lora-in-vision-language-models-efficient-fine-tuning-with-llava-c8948674d855" target="_blank" rel="noopener">Article</a>
        <a href="https://github.com/phrugsa-limbunlom/vlm-lora" target="_blank" rel="noopener">Code</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/medium/BitsAndBytes.webp" alt="Quantization" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://medium.com/ai-advances/choosing-the-right-model-size-to-your-memory-understanding-bits-bytes-and-model-quantization-6045f8fc68c3" target="_blank" rel="noopener">Choosing the Right Model Size for Your Memory: Bits, Bytes and Quantization</a></p>
      <p class="ac-entry__venue"><em>AI Advances</em></p>
      <p class="ac-links">
        <a href="https://medium.com/ai-advances/choosing-the-right-model-size-to-your-memory-understanding-bits-bytes-and-model-quantization-6045f8fc68c3" target="_blank" rel="noopener">Article</a>
        <a href="https://github.com/phrugsa-limbunlom/llm-ptq" target="_blank" rel="noopener">Code</a>
      </p>
    </div>
  </div>

  <div class="ac-entry">
    <img class="ac-entry__thumb" src="/images/medium/GAN.webp" alt="GAN" loading="lazy">
    <div>
      <p class="ac-entry__title"><a href="https://phrugsa-limbunlom.medium.com/what-you-may-miss-about-the-core-concept-of-the-gan-model-f1820d3f7efc" target="_blank" rel="noopener">What You May Miss About the Core Concept of the GAN Model</a></p>
      <p class="ac-entry__venue"><em>Medium</em></p>
      <p class="ac-links">
        <a href="https://phrugsa-limbunlom.medium.com/what-you-may-miss-about-the-core-concept-of-the-gan-model-f1820d3f7efc" target="_blank" rel="noopener">Article</a>
      </p>
    </div>
  </div>

  <p class="ac-more"><a href="/articles/">All articles &rarr;</a></p>
</section>

<section class="ac-section" id="education">
  <h2>Education</h2>
  <div class="ac-entry ac-entry--text">
    <span class="ac-entry__meta">2023 &ndash; 2024</span>
    <div><strong>MSc Artificial Intelligence and its Applications</strong> (Distinction), University of Essex<br><span class="ac-inline-list">Dissertation: Sentiment-Enhanced GAN for Financial Time-Series Forecasting</span></div>
  </div>
  <div class="ac-entry ac-entry--text">
    <span class="ac-entry__meta">2019</span>
    <div><strong>Certificate in Artificial Intelligence</strong>, ISS 2019, Sungkyunkwan University</div>
  </div>
  <div class="ac-entry ac-entry--text">
    <span class="ac-entry__meta">2016 &ndash; 2020</span>
    <div><strong>BSc Computer Science</strong>, Mahidol University</div>
  </div>
  <p class="ac-inline-list" style="margin-top:10px;">
    Certifications:
    <a href="https://www.credly.com/badges/3c9d4fda-e1e2-4bf1-b0a5-1fcf91ca3d71" target="_blank" rel="noopener">AWS ML Engineer</a> &middot;
    <a href="https://learn.microsoft.com/en-us/users/phrugsalimbunlom-0283/credentials/4e89a1228e27e99d" target="_blank" rel="noopener">Azure AI Engineer</a> &middot;
    IBM Generative AI Engineering &middot; NVIDIA AI Infrastructure &middot; Deep Learning Specialization &middot;
    <a href="https://www.credly.com/badges/aec100a4-3112-4f1b-9616-0eac251071d6" target="_blank" rel="noopener">AWS Cloud Practitioner</a>
  </p>
</section>

<section class="ac-section" id="projects">
  <h2>Engineering</h2>
  <p>Applied AI systems (agentic RAG, multi-agent platforms, LLM inference) are listed on the <a href="/projects/">Projects</a> page.</p>
</section>

</div>
