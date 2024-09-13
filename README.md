# ProBAN

Reliable information on the strength of protein interactions and their presence in physiological and pathophysiological processes is critical to the development of therapeutics and diagnostics based on the functioning of protein-protein complexes. The most accurate are experimental methods for determining binding strength, but they have a number of limitations, as well as high labor intensity and cost. Computational methods can significantly reduce the set of potential interactions to a subset of the most likely ones, which will serve as a starting point for further laboratory experiments.

In this work, the ProBAN (Protein Binding Affinity Network) algorithm was developed, based on convolutional neural networks, which predicts the value of the dissociation constant (Kd).

An example of processing one complex can be done by running Prepare_sample.ipynb

To test the model you need:

1) download the saved model (the link https://disk.yandex.ru/d/kYvSX_sCEshvEA ) and place it in the Result Model folder.

2) unpack archives with test data in the Data/Dataset_t1 and Data/Dataset_t2 folders

3) Run Test_model.ipynb


To train a model you need:
   
1) unpack the archives with data in the folders Data/Dataset_val Data/Dataset_t1 and Data/Dataset_t2 and download the archive with training data (link in Data) and unpack it into Data/Dataset. To unpack the entire dataset you will need more than 200 GB of memory.

2) Run Train_model.ipynb


