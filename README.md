# Image Search Using CLIP+VIT
A powerful image search using CLIP (Contrastive Language-Image Pre-Training) + Vision Transformer (VIT) 

CLIP (Contrastive Language-Image Pre-Training) is a neural network trained on a variety of (image, text) pairs. The above image search CLIP model is trained on 
25000 images and text from unsplash, with Vision Transformer asd a backbone model.The logic goes like this at first the embeddings from the text has been generated and then I 
have generated the image embeddings, then these embeddings are plotted in a latent space and a cosine similarity is been founded and most suitable images are shown up.

**How CLIP Works?**

<p align="center">
  <img width="800" height="300" src="CLIP.png">
</p>

For more reference you can take a look on [Openai CLIP Blog](https://openai.com/blog/clip/)

**Work in Progress**

1. Web App
2. Deploy to AWS Fragate
