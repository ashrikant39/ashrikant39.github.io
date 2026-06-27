---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---

<section class="content-hero">
  <p class="content-kicker">Projects</p>
  <h1 class="content-title">Builds focused on ML performance and deployment</h1>
  <p class="content-text">This page highlights course and personal projects with the same emphasis I use in engineering work: measurable outputs, model quality, and deployment constraints.</p>
</section>

<section class="content-section">
  <div class="content-card">
    <p class="content-kicker">Featured</p>
    <h2 class="content-title">TensorRT YOLO Segmentation Inference</h2>
    <p class="content-text">A CUDA-focused segmentation inference project aimed at fast, deployable vision workloads.</p>
    <div class="content-links">
      <a href="https://github.com/ashrikant39/yolo_seg_app">GitHub repo</a>
    </div>
    <div class="content-meta">
      <span>TensorRT</span>
      <span>CUDA</span>
      <span>YOLO</span>
      <span>Segmentation</span>
    </div>
  </div>

  <div class="content-card">
    <p class="content-kicker">University of Michigan</p>
    <h2 class="content-title">Translating Cartoon to Natural Images using Stable Diffusion</h2>
    <p class="content-text">Course project on latent diffusion generation across two image domains.</p>
    <div class="content-links">
      <a href="/files/reports/um/StableDiffusion_Cartoon_to_Natural.pdf">Report</a>
      <a href="/files/presentations/StableDiffusion_Cartoon_to_Natural_Poster.pdf">Poster</a>
    </div>
    <ul class="content-list">
      <li>Trained a latent diffusion model to generate images from both domains.</li>
      <li>Used BLIP as guidance to condition generation.</li>
    </ul>
  </div>

  <div class="content-card">
    <p class="content-kicker">University of Michigan</p>
    <h2 class="content-title">Block-based Video Compressed Sensing</h2>
    <p class="content-text">A deep learning approach to compressed sensing for natural images and videos.</p>
    <div class="content-links">
      <a href="/files/reports/um/VCSNet_Report.pdf">Report</a>
    </div>
    <ul class="content-list">
      <li>Developed a block-based compressed sensing model for natural image and video reconstruction.</li>
      <li>Achieved a 0.1 compression factor on non-keyframes of KITTI videos.</li>
    </ul>
  </div>

  <div class="content-card">
    <p class="content-kicker">University of Michigan</p>
    <h2 class="content-title">Brain Tumor Segmentation using 3D U-Nets</h2>
    <p class="content-text">An ensemble-based 3D segmentation pipeline for medical imaging.</p>
    <div class="content-links">
      <a href="/files/reports/um/Brain_Tumor_Segmentation_EECS504_Report.pdf">Report</a>
      <a href="/files/presentations/Brain_Tumor_Segmentation_EECS504_Presentation_Dec_2022.pdf">Presentation</a>
    </div>
    <ul class="content-list">
      <li>Implemented 3D U-Net variants and ensembled multiple models to reduce random errors.</li>
      <li>Predicted the whole tumor region with a dice score of 80.5 percent.</li>
    </ul>
  </div>

  <div class="content-card">
    <p class="content-kicker">NITK</p>
    <h2 class="content-title">Automatic Stroke Lesion Identification</h2>
    <p class="content-text">Residual U-Net based lesion segmentation for brain MRI volumes.</p>
    <div class="content-links">
      <a href="/files/reports/nitk/Bachelor_Thesis.pdf">Thesis</a>
    </div>
    <ul class="content-list">
      <li>Improved lesion segmentation F1-score from 51.7 percent to 56.3 percent.</li>
      <li>Used brain parcellations to improve precision for Grey Matter and White Matter regions.</li>
    </ul>
  </div>
</section>
