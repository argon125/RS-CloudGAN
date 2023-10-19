# RS_Cloud-GAN
RS_CloudGAN: A Novel Feature Map Ensemble UNet GAN Architecture for Cloud Removal from Remote Sensing Imagery

### Abstract:
The high resolution of remote sensing images is tremendously utilized in several applications. However, cloud cover, haze, and shadows inevitably affect remote sensing imagery. Hence, removing the cloud from a satellite image is an essential pre-processing step before any effective analysis. With the increasing popularity of deep learning in image processing, several architectures have been proposed to perform this task. However, the existing single-image cloud removal benchmarks do not eliminate all occlusions when thick clouds overlay the land features. Thus, in this work, we propose a novel architecture called RS CloudGAN to address this problem. The model has been trained on open-source RICE dataset images for thin and thick cloud removal. The generator of the architecture consists of different convolution heads stacked together in the encoder and decoder, a multi-head self-attention block in the bottleneck to extract critical information from encoder feature maps, and a PatchGAN discriminator. The performance has been validated using the Peak Signal Noise Ratio (PSNR) and Structural Similarity Index (SSIM) and is compared with other existing models in the literature. The proposed model outperforms the state-of-the-art results on thick cloud removal by almost 3 dB in PSNR and 4% in SSIM. Experimental validation of the trained model on real-time LandSat8 satellite data from three geographical regions with different cloud cover percentages is also performed. We conducted ablation experiments to identify the best building blocks of the architecture and the training loss function. Finally, the Class Activation Maps (CAM) for these predictions have been included for the explainability of the model results. 

### Results

Qualitative analysis:

<img width="626" alt="image" src="https://github.com/argon125/RS-CloudGAN/assets/64146402/80ee161b-860d-4532-9d54-900a44db3878">

Quantitative metrics:

<img width="391" alt="image" src="https://github.com/argon125/RS-CloudGAN/assets/64146402/c5645aa3-44da-40d6-b114-c2a07e91bcfe">
<img width="391" alt="image" src="https://github.com/argon125/RS-CloudGAN/assets/64146402/7e3e279e-3019-4470-907b-96e266df4648">


### Authors:
### Arrun Sivasubramanian(1,2), Jaya Saxena(1), , G Srinivasa Rao(1), Sowmya V(2)

### Affiliation:
### 1) NRSC, Indian Space Research Organization, Hyderabad, India
### 2) Center for Computational Engineering and Networking, Amrita School of Engineering, Coimbatore, India  

## Dataset: 

RICE Dataset taken from https://github.com/BUPTLdy/RICE_DATASET for training the model.
