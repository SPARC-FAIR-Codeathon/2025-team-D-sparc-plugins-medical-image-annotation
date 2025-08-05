# 2025-team-D-sparc-plugins-medical-image-annotation

## Table of contents
* [Summary of functionality](#summary-of-functionality)
* [How to use the plugin](#how-to-use-the-plugin)
* [Summary of technical implementation](#summary-of-technical-implementation)


## Summary of functionality
As one of the most fundamental tasks in computer-assisted clinical decision support, medical image segmentation forms the basis for numerous downstream applications ranging from diagnosis, therapeutic planning, to post-treatment monitoring and outcome evaluation. To accurately and efficiently segment anatomical structures in medical images, an AI-driven promptable segmentation plugin is introduced in this project. It integrates a state-of-the-art framework for 3D promptable segmentation: nnInteractive [1] and a web-based user interface, supporting positive and negative point prompts across multiple imaging modalities (CT, MR, PET, etc.). This model has been trained on 120+ diverse volumetric 3D datasets (CT, MRI, PET, 3D Microscopy, etc.), enabling full 3D segmentation from intuitive 2D interactions with accuracy, adaptability, and usability. 

[1] Isensee, F.*, Rokuss, M.*, Krämer, L.*, Dinkelacker, S., Ravindran, A., Stritzke, F., Hamm, B., Wald, T., Langenberg, M., Ulrich, C., Deissler, J., Floca, R., & Maier-Hein, K. (2025). nnInteractive: Redefining 3D Promptable Segmentation. https://arxiv.org/abs/2503.08373
*: equal contribution
## How to use the plugin
1. Start by launching the Medical Image Annotation plugin.
<img width="1263" height="892" alt="Screenshot from 2025-08-05 12-47-17" src="https://github.com/user-attachments/assets/d5e31e26-c0f2-413e-8282-5c0c69c12539" />
2. Click a point as a prompt with in the region of intersted. Screenshot

3. The mask will show in the medical image after around 30 seconds without GPU or 5 seconds with GPU. Screenshot


