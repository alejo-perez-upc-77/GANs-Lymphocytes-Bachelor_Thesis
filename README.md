# Generative Adversarial Networks for Peripheral Cell Blood Images Standardization

Bachelor Thesis in Biomedical Engineering (Politechnic University of Catalonia)

Our multidisciplinary research group has been developing
models based on Convolutional Neural Networks for the
automatic morphological recognition of normal, reactive and
abnormal blood cells circulating in blood, lymphoma and acute
leukaemia.
The problem addressed in this study is related to the effect of
different staining protocols used to prepare the blood smear from
which microscope images are analyzed. Specifically, the
automatic blood cell classification with models trained using an
image database collected in a single hospital may be affected
when images are coming from another hospital. Thus resulting in
a certain number of misclassified images. Such accuracy decrease
is because some color, staining and texture characteristics may
suffer variations in the images depending on the staining protocol.
Generative Adversarial Networks (GANs) were leveraged to
transform the images of the X domain (Hospital Germans Trias i
Pujol) into the Y domain (Hospital Clínic). Characteristics of
color, staining and texture of the latter were emulated. After this
transformation, the classification accuracy of the images taken at
Hospital Germans Trias i Pujol improved. CycleGAN and
ColorizationGAN architectures were used for the transformations.
ResNet 18, ResNet 34, ResNet 18 with Focal Loss and ResNet 34
with Focal Loss were used for the classifications. The
classification accuracy improved from 34% to 81%.
