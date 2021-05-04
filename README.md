# Learning Artistic Style From Language Features
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/3kTJYXo)

Doing style transfer with grounding OpenAI's CLIP.

![portrait](https://user-images.githubusercontent.com/5066934/110341080-9645cc00-7fef-11eb-8911-210d30abde93.gif)
![a van gogh starry night style painting of a modern house](https://user-images.githubusercontent.com/5066934/110341096-9940bc80-7fef-11eb-8691-3388325d0351.gif)

### Typical Style Transfer
Under normal circumstances, one would use a method like that of Gatys et al. to transfer the style of one image to the content of another. This only encompasses one photo and has no true concept of space.

### CLIP-based Style Transfer
Using a similar technique to that of Gatys et al. we trade Gram Matrices for CLIP activations. Given your image and a phrase, CLIP can transfer (somewhat successfully) the artist or painting's style that you specify!

#### Special Features of this Method
1. There is an understanding of spatial relationships. 🌌
2. Ghost faces and self-portraits. 👻
3. Abstract/general style and motif comprehension. 🎨
