# InvokeAI-Google-Colab
Colab notebook for InvokeAI 3.x.x

https://colab.research.google.com/drive/1-zm3Rkca_ix5pLdybWgjfT0xKcz6S9Yx?usp=sharing

Works with the SDXL base model and refiner on a GPU runtime. 
Other models can be added, as long as they are in diffusers format.
The free tier offers little disk space, so I'm using Google Drive to store the base model. Using only a single 16 bit model works without a connected Google Drive account.   
Runs out of RAM on Colab when trying to convert .safetensors to diffusers, so custom models can't be imported at the moment. 

The same notebook, but it downloads the latest dev version.  
https://colab.research.google.com/drive/1lgu_FK2SyjbSTFTAvpQqFdrb2201NCsC?usp=sharing
