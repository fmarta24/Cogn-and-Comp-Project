# Cogn-and-Comp-Project
This project investigates how a Deep Belief Network (DBN) learns to recognize handwritten letters from the German alphabet using a dataset of standardized grayscale character images. The model is trained to extract hierarchical representations from raw pixel inputs, enabling the study of how visual features evolve across layers.

To analyze the learned representations, linear readout classifiers are applied at different levels of the network to assess whether letter classes become more separable in deeper layers. Clustering techniques are also used to explore how distinct letter categories emerge within the hidden feature space.

Model performance is evaluated through confusion matrices to examine classification accuracy and patterns of errors. Finally, the robustness of the DBN is tested by analyzing its vulnerability to adversarial perturbations, providing insight into the stability and limitations of its learned representations.
