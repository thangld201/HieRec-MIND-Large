# HieRec-MIND-Large
Codes to run the HieRec model (ACL 2021) on MIND Large dataset under Google Colaboratory environment. 

The implementation remains almost the same as in the [original repo](https://github.com/taoqi98/HieRec), with some utilities and commands added for testing with MIND Large dataset on Google Colab. In addition, the meta data of entity is loaded directly from the MIND dataset, and the `KG_root_path` in the code is merely a placeholder. Scripts to download the MIND dataset and Glove embedding are provided in the notebooks.

By default, both the training and validation data (MIND Large) are used to train the model. Since the dataset is quite large, I also added the code to split the data into portions when training and testing.

Since these notebooks were originally run on Google Colab with GPU Tesla K80, I recommend that you use the same environment if you want to try the project.

## Repository Structures
* `Training_HieRec_MIND_Large_20211.ipynb`: Training on MIND Large
* `Evaluation_HieRec_MIND_Large_20211.ipynb`: Evaluation on MIND Large
* `Ranking_Hierec_MIND_Large_20211.ipynb`: Output ranking submission on MIND Large Test
* `HieRec_MIND_Small_20211.ipynb`: Training & Evaluation on MIND Small

## How to run
First, upload the notebooks to Google Colaboratory.

To test on MIND Small dataset, in `HieRec_MIND_Small_20211.ipynb`, from Google Colab interface, click `Runtime` --> `Run all`.

The notebooks for MIND Large follow the same patterns, except that they are made individually for training, evaluation and submission purposes.

## Credit
* [taoqi98/HieRec](https://github.com/taoqi98/HieRec)




