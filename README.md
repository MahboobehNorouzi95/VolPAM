# VolPAM
Volumetric Phenotype-Activation-Maps for Data-driven Discovery of 3D Imaging Phenotypes and Interpretability

In this project, we present a novel technique for identifying meaningful patterns in 3D medical images. Here are different steps of the project:

1. 3D convolutional autoencoder training for generating the latent representation of the images.
2. Hierarchical clustering on the latent representations for revealing distinct phenotypes.
3. 3D convolutional classifier training based on detected labels for each 3D CT scan.
4. Generating 3D, 2D, and 1D Grad-CAM visualizations of the distinct phenotypes using a new approach called Volumetric Phenotype-Activation-Map (VolMAP). 

Our method allows for the interpretation of phenotypes in terms of specific image features, such as voxels, spatial regions, and slices. The proposed technique is demonstrated using computed tomography (CT) scans, but could be applied to any 3D imaging modality. We are hoping that our approach improves understanding of disease and aid in the development of new diagnostic tools.
