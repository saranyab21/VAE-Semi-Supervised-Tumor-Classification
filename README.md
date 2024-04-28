# Improving Brain Tumor Classification Using Semi-Supervised Latent Space Learning

Recent research has emphasized the significance of classifying brain tumors to enable timely diagnosis and treatment. Magnetic Resonance Imaging (MRI), a non-invasive imaging technique, has been extensively utilized to capture the growth of tumors in brain
tissue. However, limited labeled data poses a significant challenge in training, effective deep learning models. This study addresses this issue by utilizing a semi-supervised latent
space learning approach that leverages a large amount of unlabeled data. Initially, a Variational Autoencoder (VAE) is used to learn the optimal latent vector representation of
brain MR images. Then, a shallow learner is trained using a small set of labeled latent vectors. Later, a pool of unlabeled latent vectors, obtained from a previously trained VAE encoder, is employed to fine-tune the partially trained model using a self-training strategy
of semi-supervised learning. The proposed framework has been extensively evaluated in terms of Accuracy, Precision, Recall, and F1-Score using two distinct datasets for binary
and multi-class tumor type classification. To achieve the most promising results in our model, separate experiments were conducted to determine the optimal initial size of the
labeled set and the best-performing base classifier. Moreover, the performance of the proposed model was compared with fully-supervised baselines and state-of-the-art semisupervised
brain tumor detection frameworks.

![image](https://github.com/saranyab21/VAE-Semi-Supervised-Tumor-Classification/blob/master/images/Flow_diagram.jpg)
