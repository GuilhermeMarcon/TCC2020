
# Redes Neurais Residuais Profundas para Classificação de Imagens de Placas de Petri.


The culture of microorganisms is a method used to identify and describe characteristics of a
certain colony of bacteria, which are grown in a cylindrical and flattened container, usually made
of glass or plastic, called a Petri dish. These containers are then filled with agar, a liquid broth
filled with nutrients necessary for the bacteria in question to develop. Colony morphologies
have differences in shape, size, color and texture, all dependent on the type of bacteria and the
amount / composition of the agar inserted in the plate. Thus, identifying an organism based on
these characteristics is important, but the methods are expensive and time-consuming, dependent
on a human specialist for analysis, which makes the process laborious. Therefore, the study
and development of a process to automate the identification of the microorganism by using
computational methods to identify and characterize species would be a great innovation in the
area. The objective of this work is to investigate the classification of Petri dishes images by
means of a deep residual neural network, which are considered state-of-the-art to identify objects
in images. A deep neural network has several layers, which can learn attributes at different
levels of abstraction, in a hierarchical way. While traditional machine learning methods require a
pre-processing step to extract characteristics from the images, the different levels of abstraction
of deep neural networks replace this step—allowing the identification of relevant image features
within the learning process itself. On the other hand, adding many layers in the neural network
presents the “degradation problem”, i.e., when the model starts to perform worse due to the
difficulty inherent in the training of the network. Residual neural (ResNet) networks mitigate
this degradation problem. ResNet map the network indirectly through “shortcuts” between
layer blocks, so that some layers can be ’‘skipped” during training step of the network. Among
the results obtained with the development of this work, We trained a deep residual network
that achieved an average accuracy of 0.935. When evaluated in other studies using traditional
machine learning models in this same dataset, classification models obtain less accuracy, for
example, 0.73 with the Random Forests method, 0.49 with the SVM method and 0.67 with the
KNN method. Thus, there is evidence that the proposal investigated in this work is competitive.
