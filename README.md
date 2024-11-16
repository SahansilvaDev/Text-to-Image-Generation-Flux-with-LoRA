# Text-to-Image-Generation-Flux-with-LoRA
using FLUX Dev to develop custom LoRA for generate your own images what you desire.

this dreambooth stable diffusion file can generate images using T4<br>
other files run to requires A100 GPU<br>

easy and more cost effective way to build flux with loRa is using replicate site.<br>
https://replicate.com/blog/fine-tune-flux

# Dataset Preparation
Here are some guidelines:<br>

Use 12-20 images for best results<br>
Use large images if possible<br>
Use JPEG or PNG formats<br>
Optionally, create a corresponding .txt file for each image with the same name, containing the caption<br>
<b>(if your using replicate site to train the model you do not need to worry above dataset Preparation guidelines, just need only images with variations)</b>

<b>if you use replicate site<br>
<ol>
<li>create account and add your credit card</li>
<li>search flux - (ostris/flux-dev-lora-trainer)</li>
<li>then go to hugging face and login </li>
<li>and zip your images file</li>
<li>and go to replicate flux model train tab</li>
<li>and create a model using [destination box clicking]</li>
<li>upload your images zip file to [imput images box]</li>
<li>trigger word - does not include in promt</li>
<li>steps(epochs) 1000 default (if increase steps size it would be good)</li>
<li>then go to hugging face and create new model and give name and save it plublically</li>
<li>then put hugging face model repo id to replicate site flux model train tab [hf_repo_id box]</li>
<li>then hugging face --> access tokens---> create token-->give reporitories permissions ot created model ---> generate token and copy it</li>
<li>then go to replicate site flux model train tab [hf_token box] input the copied token this box</li>
<li>create training button</li>
</ol></b>






# DREAM BOOTH method from Google research  (subject driven generation) [trigger word]<br>
https://dreambooth.github.io/

https://colab.research.google.com/github/KaliYuga-ai/DreamBoothV2fork/blob/main/DreamBooth_Stable_Diffusion_V2.ipynb?authuser=1#scrollTo=hFh6Y1Mitl7g

# Run the trained models using Comfyui<br>
https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#installing

https://comfyuiweb.com/#ai-image-generator

# Resources,
https://www.mlexpert.io/blog/flux-1-dev<br>
https://github.com/ostris/ai-toolkit<br>
https://colab.research.google.com/drive/1jbUqiqM2e_wDvNAuH6Fz61c2-I1y9siQ?authuser=1#scrollTo=zl-S0m3pkQC5<br>
https://openart.ai/blog/post/stable-diffusion-prompts-for-profile-picture<br>

