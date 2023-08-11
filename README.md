# InvokeAI-Google-Colab
Colab notebook for InvokeAI 3.0.1

https://colab.research.google.com/drive/1-zm3Rkca_ix5pLdybWgjfT0xKcz6S9Yx?usp=sharing

Works with the SDXL base model and refiner on a GPU runtime.  
The free tier will run out of space if using both, so I'm using Google Drive to store the base model. Using only the base model works without a connected Google Drive account.   
Silently fails when trying to convert .safetensors to diffusers, so custom models can't be imported at the moment. 

The same notebook, but it downloads the latest dev version.
https://colab.research.google.com/drive/1lgu_FK2SyjbSTFTAvpQqFdrb2201NCsC?usp=sharing
