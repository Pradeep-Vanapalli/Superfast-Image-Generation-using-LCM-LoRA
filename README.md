# Fastest-Image-Generation-using-LCM-LoRA
- Fastest Image Generation using LCM LoRA in 4-5 steps.
- LCM LORA:
	- * LCM stnds for Latent Consistency Model.
	- * Below are the steps to generate image very quickly.
		- 1. Select a texher model from the HF Hub
			- * SDXL base model or fintuned Dreambooth Model.
		- 2. Learn LCM LoRA on the model. 
		- 3. Use LoRA with any SDXL and LCM schedular.
	- * We gonna use diffusers to perform high speed inferencing using LCM LoRA.
	- * These are the practical steps below:
		- 1. Diffusion pipeline using SDXL(base)
		- 2. Apply "LCM LoRA"
		- 3. Change Schedular to LCm Schedule.

## References:
- https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0
- Research Paper: https://arxiv.org/abs/2311.05556
- https://github.com/huggingface/diffusers
- https://www.youtube.com/watch?v=Js9M9SZabAU&t=243s
