# IIoT deep malware threat hunting: from adversarial example detection to adversarial scenario detection

![image](https://user-images.githubusercontent.com/29665874/196861914-ebbf5770-cfb2-4eea-9350-7dafeb786b13.png)

Protecting widely-used deep classifiers against
black-box adversarial attacks is a recent research challenge in
many security-related areas, including malware classification.
This class of attacks relies on optimizing a sequence of highly
similar queries to bypass given classifiers. In this paper, we
leverage this property and propose a history-based method
named, Stateful Query Analysis (SQA), which analyzes sequences
of queries received by a malware classifier to detect black-box
adversarial attacks on an Industrial Internet of Things (IIoT).
In the SQA pipeline, there are two components, namely the
similarity encoder and the classifier, both based on Convolutional
Neural Networks (CNNs). Unlike state-of-the-art methods, which
aim to identify individual adversarial examples, tracking the
history of queries allows our method to identify adversarial
scenarios and abort attacks before their completion. We optimize
SQA using different combinations of hyperparameters on an
ARM-based IIoT malware dataset, widely adopted for malware
threat hunting in Industry 4.0. The use of a novel distance metric
in calculating the loss function of the similarity encoder results in
more disentangled representations and improves the performance
of our method. Our evaluations demonstrate the validity of SQA
via a detection rate of 93.1% over a wide range of adversarial
examples.
