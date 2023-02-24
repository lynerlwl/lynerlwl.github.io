What is image segmentation?
- Image segmentation is vital scene understanding process that locate objects and boundaries in an image. 

What image contain?
- Image is composed by pixels with different intensity value.

How semantic segmentation is done?
- Semantic segmentation is a task that classify each pixel in the image to a label.

CNN learn the changes among a set of connected pixels. Prominent changes and repeated parts will be in learnt model.

**Long-term context relationship** refers to the relationship between different regions or objects in an image over a longer period of time.

**Contextual information** refers to the information that surrounds a specific object or region in an image, that can be useful for disambiguating objects or making more accurate predictions.

Conditional Random Field (CRF) allows the model to take into account the relationship between different regions in an image.

How it is being done?
- Traditional CV algorithm
  - thresholding
  - histogram-based bundling
  - region growing
  - k-means clustering 
  - watersheds
  - active contours
  - graph cuts
  - conditional and Markov random fields
  - sparsity based methods
 
How people doing it now?
  - Deep Learning
  - Fully convolutional networks / fully convolutional pixel-labeling networks
  - Convolutional models with graphical models
  - Encoder-decoder based models
  - Multi-scale and pyramid network based models
  - Dilated convolutional models and DeepLab family
  - Recurrent neural network based models
  - Attention-based models
  - Generative models and adversarial training
  - Convolutional models with active contour models

What's the problem with this task?
    - While the deep learning model is capable to achieve good segmentation result, the technique is highly dependent on big dataset for training. 

How this review address the problem?

how to effectively construct robust feature representations

Application
- scene understanding
- medical image analysis [1]
- remote sensing [6]
- autonomous driving [34]
- robotic perception
- video surveillance
- augmented reality
- image compression

