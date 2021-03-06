
# FeatureGan
## Nicolas Cruz, Javier-Ruiz del Solar

## University of Chile
### Code available at:
[pytorch code](https://github.com/nicolasCruzW21/FeatureGan-pytorch)

<img align="center" src="https://github.com/nicolasCruzW21/FeatureGan/blob/master/FeatureGan/page2.png?raw=true">
### Abstract

Image-to-image  translation  is  a relevant problem with many applications in computer vision and robotics. This paper presents a methodology for learning to translate images using an unpaired image training set. This methodology is based on the use of Generative Adversarial Networks (GAN) and has three main novel components: (i) the use of a feature loss to ensure alignment between the input and the generated image, (ii) the use of a feature pyramid discriminator, which uses a tensor composed of features at different levels of abstraction as input to the discriminator, and (iii) the introduction of a per class loss to improve the results in the simulation-to-reality task. By using the proposed methodology, the generator is encouraged to preserve the geometric layout of the input image in the output image meaning that the input and output images are aligned. The main advantage of the proposed methodology is a more stable training process, which includes a higher resilience to common GAN problems such as mode collapse, as well as better and more consistent results. The proposed methodology is also fast to train and easy to replicate. The reported experiments show the successful use of the proposed methodology in three different applications: sim-to-real image translation, horse-to-zebra image translation and horse-to-elephant image transfiguration.


### Horse to elephant
<p align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=9CAol4XoN4k
  " target="_blank"><img src="http://img.youtube.com/vi/9CAol4XoN4k/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="480" height="320" border="10" /></a>
</p>

### Horse to zebra
<p align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=KoY6hfojSQM
  " target="_blank"><img src="http://img.youtube.com/vi/KoY6hfojSQM/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="480" height="320" border="10" /></a>
</p>

### Simulation to Reality
<p align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=faJifSb2c1E
  " target="_blank"><img src="http://img.youtube.com/vi/faJifSb2c1E/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="480" height="320" border="10" /></a>
</p>
