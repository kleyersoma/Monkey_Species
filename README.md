# Classification of 10 Monkey Species and More

In this repository an image classifier for monkey species will be developed, the species that this image classifier will be allowed to
identify are:

* Mantled Howler
* Patas Monkey
* Bald Uakari
* Japanese Macaque
* Pygmy Marmoset
* White Headed Capuchin
* Silvery Marmoset
* Common Squirrel Monkey
* Black Headed Night Monkey
* Nilgiri Langur
* And More species

## How will new species be indentified and classified?

New species are going to be identified and classified thanks to techniques such as [One Shot Learninig](https://en.wikipedia.org/wiki/One-shot_learning).
The new species will be classified as ***new_monkey_species_#***

##Model Development
The model will be developed using [Tensorflow 2.X](https://www.tensorflow.org/)
The process of development of the OSL Neural Network will have the next steps, therefore the model will have these features:
* Train with Adversarial Learning
* Robustness against Adversarial Attacks
* Label Smoothing
* Post Training Quantization
* Weight Pruning

## Model Deployment
The OSL Neural Network that will be developed is going to be implemented in an API with [Django REST](https://www.django-rest-framework.org/), 
the deployment process will be explained in pdf file, which will be found in this repository.

### Note
The dataset that was used for training the OSL NN was obtained from [Kaggle Monkey Species](https://www.kaggle.com/slothkong/10-monkey-species)

### Dataset Acknowledgements
Thanks to Gustavo Montoya, Jacky Zhang and Sofia Loaiciga for their help with the dataset curation
