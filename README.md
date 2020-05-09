# EMNLP 2020 

## **Preparing the data**

Before running of the ipynb files that create models,  obtain the dataset from 
[U Rochester's website](https://www.cs.rochester.edu/u/nhossain/humicroedit.html)
and run `Engineer_Features.ipynb` to do prepatory work on the data.

- From the above link, obtain the file with the base training samples and the file with extra training data.
- Set the paths in `dfs_train_path` to point to those files
- Obtain the testing file(s)
- Set the path in `dfs_test_path` to point to those file(s)
- Set the paths in the last few cells of `Engineer_Features.ipynb` to point to where you want your prepared data to be. 

[GloVe embeddings](https://nlp.stanford.edu/projects/glove/) are also used throughout this project. 
Please download and adjust paths to the embedding on your own system. (We used the 42B.300d embedding for our tasks.)

Once the paths to the training/testing files, the embedding, and the output files are in place, you can run `Engineer_Features.ipynb` to produce two files, one file for the combined **training data**, and another file for the **testing data**. These two files are imported and used throughout the project for all the models. 

The models are in the files with their respective names.
To run each model, please adjust the path to the training, the testing data as well as the GloVe embedding on your system. 

Thank you and please let us know if you have any questions regarding our project.
We are more than happy to answer questions face to face on a zoom call.

Sincerely, </br>
Zirong Chen | zc157@georgetown.edu </br>
Haotian Xue | hx82@georgetown.edu </br>
Yuansheng Xie | yx131@georgetown.edu </br>

