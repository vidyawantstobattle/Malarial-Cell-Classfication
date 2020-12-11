# Malarial-Cell-Classfication
Malarial Cell Classification. Current work being carried out on this project to use VGG models for image segmentation using the same dataset. <br />

Dataset for this project can be found at: https://lhncbc.nlm.nih.gov/publication/pub9932 <br />
Or at: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria <br />

Classification done for cells containing malaria parasite.
Key operations done include image resizing, defining and training of the model with keras layers and plotting the 
evaluation of loss and accuracy through the epochs using matplotlib.

Note that it is recommended to use the datasets from the links specified above as opposed to the one I have uploaded. The one I have uploaded will give you
a maximum accuracy of around 85-86%, even with a 100 or so epochs.

In contrast, training on the whole dataset gives you an accuracy of about 93% just with 5 epochs.
