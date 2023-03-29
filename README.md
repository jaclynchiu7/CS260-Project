# AI-powered Ad Creatives Generation and Campaign with Hydroflasks

Generating product advertisements for companies is an inefficient and difficult process to implement manually. The goal is to provide insights into whether AI can generate advertisements while still preserving the quality and purpose of the product. For our AI model, we chose DreamBooth, a diffusion-based text-to-image generation model that utilizes stable diffusion 1.5, to generate personalized images based on unique identifiers (hydroflasks). We then conducted a survey using a mix of AI-generated output images and real images to evaluate the quality of generated images. 

# Examples of Training Images 
<p align = "left">
  <img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228394871-55ec6491-da13-422d-9dd8-b3023ebd5320.jpg">
  <img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228395056-bf9aa6aa-97a6-46bd-913e-7b90fe67edbe.jpg">
  <img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228395768-c1359087-1925-4b90-b189-9c7c23c861c1.jpg">
  <img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228395777-6e79d314-30e9-4307-8666-f7cb5a6f3c59.jpg">

</p>


# Example of Output Images from Model 

The dreambooth model was trained using a white YETI cooler in different settings with the token 'photo of yeti cooler'. Once trained, various prompts such as the following were imputted into the model:

<img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228395117-f7c1f28c-2426-43a7-ab62-6311bbb27b6f.png">

'photo of yeti cooler by rocks on a hiking trail'


<img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228395127-b1059467-fb03-4c5a-b9d1-022ee521a3ec.png">

'black photo of yeti cooler in a picinic setting'


<img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228396388-f65d41a2-6c5c-44a0-9d38-8279ad6701a0.png">

'photo of yeti cooler inside a car'


<img width = "350" height = "350" src = "https://user-images.githubusercontent.com/72675054/228396360-a6261f45-353a-4b69-b99f-54d100f30f76.png">

'photo of yeti cooler at a campsite in the forest'

