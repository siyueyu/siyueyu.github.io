---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .home-hero {
    background: linear-gradient(135deg, #eef5ff 0%, #f7fbff 45%, #f0faf7 100%);
    border: 1px solid #dbeafe;
    border-radius: 22px;
    padding: 34px 38px;
    margin-bottom: 30px;
    box-shadow: 0 10px 28px rgba(30, 64, 175, 0.08);
  }

  .home-hero h1 {
    font-size: 36px;
    margin-top: 0;
    margin-bottom: 8px;
    color: #111827;
  }

  .home-hero .subtitle {
    font-size: 18px;
    color: #374151;
    margin-bottom: 18px;
    font-weight: 500;
  }

  .home-hero p {
    font-size: 16px;
    color: #374151;
    line-height: 1.75;
  }

  .tag-row {
    margin-top: 20px;
  }

  .tag {
    display: inline-block;
    padding: 7px 13px;
    margin: 4px 6px 4px 0;
    border-radius: 999px;
    background: #ffffff;
    color: #1d4ed8;
    border: 1px solid #bfdbfe;
    font-size: 13px;
    font-weight: 500;
  }

  .button-row {
    margin-top: 24px;
  }

  .home-button {
    display: inline-block;
    padding: 10px 18px;
    margin: 5px 8px 5px 0;
    border-radius: 10px;
    background: #2563eb;
    color: #ffffff !important;
    text-decoration: none;
    font-size: 14px;
    font-weight: 600;
  }

  .home-button:hover {
    background: #1d4ed8;
    text-decoration: none;
  }

  .home-button.green {
    background: #0f766e;
  }

  .home-button.green:hover {
    background: #115e59;
  }

  .home-button.gray {
    background: #374151;
  }

  .home-button.gray:hover {
    background: #1f2937;
  }

  .card-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px;
    margin: 26px 0;
  }

  .info-card {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    padding: 24px 26px;
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.045);
  }

  .info-card h2 {
    margin-top: 0;
    font-size: 21px;
    color: #111827;
    border-bottom: 2px solid #e5e7eb;
    padding-bottom: 8px;
  }

  .info-card p {
    color: #374151;
    line-height: 1.7;
  }

  .info-card ul {
    padding-left: 20px;
  }

  .info-card li {
    margin-bottom: 8px;
    line-height: 1.6;
  }

  .full-card {
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    padding: 25px 28px;
    margin: 24px 0;
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.045);
  }

  .full-card h2 {
    margin-top: 0;
    color: #111827;
    border-bottom: 2px solid #e5e7eb;
    padding-bottom: 8px;
  }

  .news-item {
    padding: 10px 0 10px 14px;
    border-left: 4px solid #2563eb;
    margin-bottom: 12px;
    color: #374151;
  }

  .paper-item {
    margin-bottom: 16px;
    line-height: 1.65;
  }

  .paper-title {
    font-weight: 700;
    color: #111827;
  }

  .paper-venue {
    color: #4b5563;
    font-style: italic;
  }

  @media (max-width: 800px) {
    .card-grid {
      grid-template-columns: 1fr;
    }

    .home-hero {
      padding: 26px 24px;
    }

    .home-hero h1 {
      font-size: 30px;
    }
  }
</style>

<div class="home-hero">
  <h1>Siyue Yu</h1>

  <div class="subtitle">
    Assistant Professor in Computer Vision and Artificial Intelligence
  </div>

  <p>
    I am an Assistant Professor at Xi'an Jiaotong-Liverpool University. My research focuses on
    computer vision, weakly supervised learning, semantic segmentation, visual foundation models,
    industrial anomaly detection, point cloud understanding, and multimodal visual perception.
  </p>

  <div class="tag-row">
    <span class="tag">Computer Vision</span>
    <span class="tag">Weakly Supervised Learning</span>
    <span class="tag">Visual Foundation Models</span>
    <span class="tag">Semantic Segmentation</span>
    <span class="tag">Anomaly Detection</span>
    <span class="tag">3D Scene Understanding</span>
  </div>

  <div class="button-row">
    <a class="home-button" href="/publications/">Publications</a>
    <a class="home-button green" href="/research/">Research</a>
    <a class="home-button gray" href="/teaching/">Teaching</a>
  </div>
</div>

<div class="card-grid">
  <div class="info-card">
    <h2>Research Focus</h2>
    <p>
      My research aims to reduce annotation costs and improve the generalization ability of
      visual perception models in open and complex scenarios.
    </p>
    <ul>
      <li>Weakly supervised semantic segmentation</li>
      <li>Foundation-model-driven dense prediction</li>
      <li>Open-world and open-vocabulary perception</li>
      <li>Efficient visual understanding</li>
    </ul>
  </div>

  <div class="info-card">
    <h2>Recruitment</h2>
    <p>
      I am looking for motivated students interested in computer vision, artificial intelligence,
      weakly supervised learning, visual foundation models, and industrial anomaly detection.
    </p>
    <p>
      Students with strong programming skills and research interests are welcome to contact me.
    </p>
  </div>
</div>

<div class="full-card">
  <h2>Selected Publications</h2>

  <div class="paper-item">
    <div class="paper-title">
      Frozen CLIP-DINO: A Strong Backbone for Weakly Supervised Semantic Segmentation
    </div>
    Bingfeng Zhang, <strong>Siyue Yu</strong>, Jimin Xiao, Yunchao Wei, Yao Zhao<br>
    <span class="paper-venue">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</span>, 2025<br>
    <a href="https://ieeexplore.ieee.org/abstract/document/10891864" target="_blank">[PDF]</a>
    <a href="https://github.com/zbf1991/WeCLIP" target="_blank">[Code]</a>
  </div>


  <p>
    <a href="/publications/">View full publication list →</a>
  </p>
</div>

<div class="full-card">
  <h2>News</h2>

  <div class="news-item">
    <strong>2026:</strong> I am looking for motivated students interested in computer vision,
    weakly supervised learning, visual foundation models, and industrial anomaly detection.
  </div>

  <div class="news-item">
    <strong>2026:</strong> We got 1 paper accepted by ECCV2026. Congrats to the master student Shuwei Wu!
  </div>
</div>
