# Handwriting-GAN
## Amogh Shreedhar Inamdar, Anagha M Rajeev, Sindhuja V Rai

A system for efficiently generating large amounts of text using comditional Least-Squares Generative Adversarial Networks (c-LSGANs) for character-wise handwriting generation and a heuristic for generating handwriting images of input text.

Input ASCII text is processed character-by-character. Each character of the text is encoded and used to generate a corresponding image of that character. These images are stitched together to form a handwritten version of the input text.

We have also developed a simple handwriting generation web app. Input text is captured and a Flask backend interfaces with our Python module to generate handwriting (using Keras over Tensorflow).
