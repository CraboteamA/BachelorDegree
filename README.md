# BachelorDegree
Thesis: Statistical aspects of neural network during multiple-fine-tuning

The main focus of this thesis is the collection and comparison of statistical data of neural
networks with and without multiple tuning to highlight the advantages of this method
and effectively use the acquired knowledge of machine learning in the diagnosis of
Parkinson’s disease.

As base was used the VGG16 model with pre-trained weights from the ImageNet dataset,
excluding the top (classification) layer. My goal was to fine-tune two different datasets -
MNIST(handwritten digits) and UJIpen(handwritten characters). In result, the final tuning
was on the HPDSpiral(consisting of handwritten spirals of both healthy and diagnosed
Parkinson's patients) dataset. Then I visualized the results of training weights and
compared them to each other to highlight the advantage of the multiple-fine-tuning
approach.

Used technologies: TensorFlow and Keras, numpy, VGG16 Model, Callbacks, Model
optimizers, loading and preprocessing of data
