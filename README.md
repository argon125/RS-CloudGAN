# RS_Cloud-GAN
RS_CloudGAN: A Novel Feature Map Ensemble UNet GAN Architecture for Cloud Removal from Remote Sensing Imagery

### Authors:
### Arrun Sivasubramanian, Jaya Saxena, Sowmya V

Abstract:
The high resolution of remote sensing images has been tremendously utilized in several
surveillance applications. However, cloud cover, haze, and shadows inevitably affect remote
sensing imagery. Hence, removing the cloud from these satellite images is an essential 
preprocessing step before any effective analysis. 
With the increasing popularity of deep learning in several image processing tasks, several architectures 
have been proposed to perform this task. However, the existing benchmarks do not eliminate all 
occlusions when thick clouds overlay the land features. Thus, in this work, we propose a novel 
architecture called RS_CloudGAN to address this problem. The model has been trained on paired 
open-source RICE dataset images for thin and thick cloud removal. The generator of the architecture
consists of different convolution heads stacked together to generate feature maps and a
PatchGAN discriminator. The performance has been validated using metrics such as Peak
Signal Noise Ratio (PSNR) and the Structural Similarity Index (SSIM). The performance of
RS_Cloud GAN is compared with the existing models, such as Pix2Pix LandSat8 satellite data
with different cloud cover percentages. The proposed model outperforms the current
benchmark state-of-the-art results on the thick cloud removal by almost 3 dB in the PSNR ratio
and 4% on the structural similarity index. Finally, the Class Activation Maps (CAM) have been
included for the explainability of the model.
