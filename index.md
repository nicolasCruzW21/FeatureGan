## FeatureGan

Nicolas Cruz, Javier-Ruiz del Solar

University of Chile

<img src="/FeatureGan/page.jpg">

### Abstract

Image-to-image  translation  is  a relevant problem with many applications in computer vision and robotics. This paper presents a methodology for learning to translate images using an unpaired image training set. This methodology is based on the use of Generative Adversarial Networks (GAN) and has three main novel components: (i) the use of a feature loss to ensure alignment between the input and the generated image, (ii) the use of a feature pyramid discriminator, which uses a tensor composed of features at different levels of abstraction as input to the discriminator, and (iii) the introduction of a per class loss to improve the results in the simulation-to-reality task. By using the proposed methodology, the generator is encouraged to preserve the geometric layout of the input image in the output image meaning that the input and output images are aligned. The main advantage of the proposed methodology is a more stable training process, which includes a higher resilience to common GAN problems such as mode collapse, as well as better and more consistent results. The proposed methodology is also fast to train and easy to replicate. The reported experiments show the successful use of the proposed methodology in three different applications: sim-to-real image translation, horse-to-zebra image translation and horse-to-elephant image transfiguration.

{% include youtubePlayer.html id="9CAol4XoN4k" %}

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Horse to zebra

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nicolasCruzW21/FeatureGan.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
