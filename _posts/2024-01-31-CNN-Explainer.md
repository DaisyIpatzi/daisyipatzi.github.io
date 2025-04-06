---
title: "Understanding CNNs with CNN Explainer"
subtitle: "A High Level Description of Convolutional Neural Networks Architecture"
date: 2024-01-31 00:00:00
description: "Understanding CNNs with CNN Explainer: A High Level Description of Convolutional Neural Networks Architecture"
featured_image: "images/demo/cnn-explainer-image.jpg"
---


## Understanding CNNs with CNN Explainer: A High Level Description of Convolutional Neural Networks Architecture

Convolutional Neural Networks (CNNs) are specialised classifiers designed to handle complex image recognition tasks. By leveraging the principles of artificial neural networks, CNNs are capable of recognising spatial patterns and hierarchies within visual data. The CNN Explainer is an interactive educational tool that provides a high-level yet intuitive breakdown of CNN structures and operations, helping users grasp both foundational and intricate elements of CNNs.

At the core of CNNs are tensors, neurons, and weighted connections that work in unison across multiple layers. These layers process input data through a series of mathematical operations, transforming raw pixels into meaningful features that can be used for classification or detection. The convolutional layers, in particular, serve as the primary mechanism for feature extraction. Using learnable filters (or kernels), these layers slide over the input image, detecting features like edges, textures, and patterns that are crucial for understanding image content.

Hyperparameters—such as kernel size, stride, and padding—play a significant role in shaping the behaviour and performance of CNNs. Kernel size determines the window through which features are captured, stride affects how far the window moves across the input, and padding helps preserve spatial dimensions during convolution. Careful tuning of these parameters can influence a model's accuracy, generalisability, and computational efficiency.

The narrative also explores activation functions, highlighting Rectified Linear Units (ReLU) and Softmax. ReLU introduces non-linearity, allowing CNNs to model complex relationships between inputs and outputs. This is essential for enabling the network to make accurate distinctions between different classes. Meanwhile, the Softmax function operates in the final layer of the network, converting raw output scores into probability distributions. This is particularly important in multi-class classification tasks, as it ensures that predictions are interpretable and normalised.

The architecture also incorporates pooling layers—such as max pooling—which reduce the spatial dimensions of feature maps while retaining the most salient information. This not only improves computational efficiency but also reduces the risk of overfitting. Flatten layers then transform the pooled features into a one-dimensional vector, which can be passed to fully connected (dense) layers for final classification.
A notable strength of the CNN Explainer lies in its ability to visually represent the inner workings of these networks. It provides real-time animations that demonstrate how data flows through each layer, making abstract concepts more tangible. This visualisation helps users understand the hierarchical nature of CNNs—how initial layers capture simple features and deeper layers combine them to form complex representations.

Overall, the CNN Explainer offers a comprehensive and accessible overview of CNNs. It not only demystifies the individual components of the architecture but also illustrates how they work together to enable high-performance image recognition. This makes it a valuable resource for learners, educators, and practitioners alike who seek to deepen their understanding of deep learning and computer vision. However, while the tool succeeds in visualising core architectural elements, it may oversimplify certain technical nuances, potentially leading to gaps in understanding for more advanced users. Additionally, the explainer largely focuses on standard CNNs and does not extend to recent innovations such as ResNets or attention mechanisms, which limits its scope in an evolving field. Thus, while it serves as an excellent introductory resource, it should ideally be supplemented with deeper theoretical study and practical experimentation for those pursuing mastery in neural network design and application.

The CNN Explainer can be found in [this link](https://poloclub.github.io/cnn-explainer/).  

## References

Wang, J., Turko, R., Shaikh, O., Park, H., Das, N., Hohman, F., Kahng, M. and Chau, P. (2020a). _CNN Explainer_. [online] poloclub.github.io. Available at: https://poloclub.github.io/cnn-explainer/ [Accessed 31 Jan. 2024].

Wang, Z.J., Turko, R., Shaikh, O., Park, H., Das, N., Hohman, F., Kahng, M. and Chau, D.H. (2020b). _CNN Explainer: Learning Convolutional Neural Networks with Interactive Visualization_. arXiv:2004.15004 [cs]. [online] Available at: https://arxiv.org/abs/2004.15004 [Accessed 31 Jan. 2024].
