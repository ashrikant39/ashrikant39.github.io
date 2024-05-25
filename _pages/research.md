---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
classes: wide
---

<!-- ### Manuscript (in preparation)
{: style="font-size:.85em; color: #7a8288;"}
---

**Computational modeling of electrophysiology recordings can predict octopus arm movement**, *Nitish Gedela, Sachin Salim, Julianna Richie, Autumn Mclane Svoboda, Cynthia Chestek, Anne Draelos, Galit Pelled*, *2023* -->

# Labs
<!-- ### Neuroscience <i class="fas fa-brain" aria-hidden="true">
{: style="font-size:.85em; color: #7a8288;"}
--- -->

**[Kim's Lab](https://kim.engin.umich.edu/)**, *University of Michigan* <span class="pull-right">May 2023 – Present</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Hun-Seok Kim, Assistant Professor, EECS</span>
<br><i class="fas fa-plus small-grey"></i> Proposed and implemented improvements to the diffusion sampling algorithms for inverse imaging problems, enhancing the quality and fidelity of the samples of latent diffusion models, achieving an FID score of 37.2, an improvement of 17.2% over the baseline model.
<br><i class="fas fa-plus small-grey"></i> Applied latent diffusion models to simulate a source and channel decoding system using diffusion denoising, resulting in a reconstruction PSNR of 24.4 dB using DDIM sampling on a channel SNR of 0 dB.
<br><i class="fas fa-plus small-grey"></i> Currently working on LiDAR point cloud upsampling in the BEV space using diffusion posterior sampling.

**[Burris' Lab](https://burris.lab.medicine.umich.edu/)**, *University of Michigan* <span class="pull-right">Aug 2022 – Apr 2023</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Nicholas Burris, Associate Professor, Radiology</span>  
<br><i class="fas fa-plus small-grey"></i> Trained an attention-UNET-based model for aortic segmentation, enhancing the accuracy and efficiency of the Vascular Deformation Mapping pipeline, resulting in an improvement of 3% in the F1-score, particularly around aortic walls.
<br><i class="fas fa-plus small-grey"></i> Implemented corrections to an Elastix-based CT Registration Pipeline, improving the elastic registration performance of the pipeline for large deformations in the aortic walls. The corrections resulted in the detection of tissue growth by an improved recall of 8%.


**[PLRI Lab](https://plri.de/)**, *Technische Universit ̈at Braunschweig* <span class="pull-right">May 2021 – Oct 2021</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Thomas Deserno, Full Professor, Medical Informatics</span>  
<br><i class="fas fa-plus small-grey"></i> Developed an efficient codebase for training and testing for semantic segmentation of sclera regions in the eye images.
<br><i class="fas fa-plus small-grey"></i> Acquired partial annotations using a game where the partial masks are saved as players competed for scoring regions.
<br><i class="fas fa-plus small-grey"></i>Acquired an F1 score of 0.94 on the test segmentation set using multiple partial annotations.


# Publications

A Chanchal, S Lal, D Barnwal, P Sinha, S Arvavasu, and J Kini. Evolution of Livernet 2.x: Architectures for automated liver cancer grade
classification from HE stained liver histopathological images. Multimedia Tools and Applications ([paper](https://link.springer.com/article/10.1007/s11042-023-15176-5#:~:text=LiverNet%202.0%20uses%20a%20modified,in%20a%20tree%2Dlike%20fashion.)). 


# Projects
### University of Michigan
{: style="font-size:.85em; color: #7a8288;"}
---
**Translating Cartoon to Natural Images using Stable Diffusion** <span class="pull-right">Oct 2023 – Dec 2023</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Stella Yu (EECS 542: Advanced Computer Vision)</span>  
[Report](/files/reports/um/StableDiffusion_Cartoon_to_Natural.pdf) | [Poster](/files/presentations/StableDiffusion_Cartoon_to_Natural_Poster.pdf)
<br><i class="fas fa-plus small-grey"></i> Trained a latent diffusion model to unconditionally generate images of both domains
<br><i class="fas fa-plus small-grey"></i> Used a pre-trained image captioning model (BLIP) as a guidance to condition the diffusion generation.

**Block-based Video Compressed Sensing** <span class="pull-right">Feb 2023 - April 2023</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Clayton Scott (EECS 553: Machine Learning)</span>  
[Report](/files/reports/um/VCSNet_Report.pdf) 
<br><i class="fas fa-plus small-grey"></i> Innovated a block-based compressed sensing approach for natural images and videos, leveraging deep learning inspired by the insights from the paper [Video Compressed Sensing using Convolutional Neural Networks](https://ieeexplore.ieee.org/document/9025255).
<br><i class="fas fa-plus small-grey"></i> Trained the model and achieved a compression factor of 0.1 on non-keyframes of videos of [Kitti Dataset](https://www.cvlibs.net/datasets/kitti/)


**Brain Tumor Segmentation using an ensemble of 3D U-Nets** <span class="pull-right">Oct 2022 - Dec 2022</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Andrew Owens (EECS 504: Graduate Computer Vision)</span>  
[Report](/files/reports/um/Brain_Tumor_Segmentation_EECS504_Report.pdf) | [Presentation](/files/presentations/Brain_Tumor_Segmentation_EECS504_Presentation_Dec_2022.pdf)
<br><i class="fas fa-plus small-grey"></i> Implemented 3D U-net, a deep convolutional neural network, to segment subregions of brain tumor
<br><i class="fas fa-plus small-grey"></i> Created an ensemble of multiple models trained with different hyper-parameters to reduce random errors
<br><i class="fas fa-plus small-grey"></i> Predicted the whole tumor region with a high dice score of 80.5%


### NITK
{: style="font-size:.85em; color: #7a8288;"}
---

**Automatic Stroke Lesion Identification** <span class="pull-right">Sep 2021 - Nov 2021</span>  
<span class="small-grey"><i class="fas fa-user" aria-hidden="true"></i> Dr. Deepu Vijayasenan (Bachelor's Thesis)</span>\
[Report](/files/reports/nitk/Bachelor_Thesis.pdf)
<br><i class="fas fa-plus small-grey"></i> Developed a method for segmenting stroke lesions in brain MRI volumes, utilizing deep 3-D convolutional networks (Residual-UNETs). This approach aimed to enhance the accuracy of stroke risk assessment in patients.
<br><i class="fas fa-plus small-grey"></i> Improved the lesion segmentation F1-score from 51.7% to 56.3% by incorporating brain parcellations into Grey Matter (GM) and White Matter (WM), improving the precision of diagnosis.
