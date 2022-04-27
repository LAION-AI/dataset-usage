# dataset-usage
This repository is a summary of all systems and scientific papers that use LAION datasets.

## Papers citing LAION datasets

After the release of LAION-400M, several papers used LAION-400M for image generation, text to image generation, image to text generation and text image matching:

- (Vector Quantized Diffusion Model for Text-to-Image Synthesis)[https://arxiv.org/abs/2111.14822.pdf] used LAION-400M to train VQ diffusion text to image generation models
- High-Resolution Image Synthesis with Latent Diffusion Models used a subset of LAION-400M to train latent diffusion models
- General Facial Representation Learning in a Visual-Linguistic Manner LAION-400M face subset to train a face clip
- BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation image captioning using LAION-400M subset
- MAGMA – Multimodal Augmentation of Generative Models through Adapter-based Finetuning was trained on image question answering using a LAION-400M subset

## Models trained on LAION datasets

### GLIDE finetuning

Clay Mullis (alias afiaka87) used subsets of LAON-2B to fine-tune the OpenAi Glide model and managed to reintroduce human generations. Samples

https://replicate.com/afiaka87/laionide-v3 
https://wandb.ai/afiaka87/glide_compare/reports/Finetuning-GLIDE-on-Laion5B–VmlldzoxNTg3MTkz
https://wandb.ai/afiaka87/laionide-v3-glide/reports/Laionide-Version-3-Benchmark–VmlldzoxNjE0MTE3

### CLOOB

https://github.com/crowsonkb/cloob-training
