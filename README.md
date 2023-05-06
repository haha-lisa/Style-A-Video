# Style-A-Video
# Agile Diffusion for Arbitrary Text-based Video Style Transfer
This is the official PyTorch implementation of the paper [''Style-A-Video: Agile Diffusion for Arbitrary Text-based Video Style Transfer'']

## Teaser

## Abstract
Large-scale text-to-video diffusion models have demonstrated an exceptional ability to synthesize diverse videos. However, due to the lack of extensive text-to-video datasets and the necessary computational resources for training, directly applying these models for video stylization remains difficult. Also, given that the noise addition process on the input content is random and destructive, fulfilling the style transfer task's content preservation criteria is challenging. This paper proposes a zero-shot video stylization method named Style-A-Video, which utilizes a generative pre-trained transformer with an image latent diffusion model to achieve a concise text-controlled video stylization. We improve the guidance condition in the denoising process, establishing a balance between artistic expression and structure preservation. Furthermore, to decrease inter-frame flicker and avoid the formation of additional artifacts, we employ a sampling optimization and a temporal consistency module. Extensive experiments show that we can attain superior content preservation and stylistic performance while incurring less consumption than previous solutions.
