# brain_tumor_classification_dlmi_2020
Classification of Brain Tumors from MRI Images Using a Capsule Classifier and Image Synthesis

# Abstract
The biggest problem for classifying magnetic resonance images (MRI) with deep learning techniques lies in the number of labelled data. 
Although recent works in the field of neural network have shown promising abilities of classifying brain tumors from brain MRI images, 
they used very deep and complex network architectures. 
Simpler network architecture requires fewer resources, and enable to use real time applications on mobile platforms. 
To this end, we introduce a new deep learning method to classify brain tumor of three tumor types. 
Our solution combines synthesise of additional data using a conditional generative model, with a new convolutional capsule architecture for the classification.

We evaluated the performance both qualitatively and quantitatively. 
Qualitatively, the conditional GAN was capable at synthesising images of different appearance, for the same underlying skull geometry. 
Moreover,  the features learned by the conditional GAN are often semantically meaningful groups, covering structures such as skull and tumor. 
The classificaiton performance was evaluated quantitatively using accuracy and F1 measures. 
The best results of 93\% accuracy and F1 score of 92\%, were obtained when the classifier pre-trained 
on 7,000 synthesised images and then trained on the original data using a 7-fold cross-validation. 
Our method performs as well as the Resnet50 state-of-the-art deep network, with 9x less parameters.
