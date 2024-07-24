# soi_auwaves_crue
This repository contains our implementation for the Auburn Waves Competition by the Space and Data Science Club. 

## Installing Dependencies
Install the required python packages using `requirements.txt` by running the following command in your terminal

```
pip install -r requirements.txt
```
or
```
conda install -r requirements.txt
```

## File Guide
1. `train_dataset/test_dataset`: Contain the labelled data that is used for training and the unlabelled data.
2. `train.csv`: Class data of the training set 
3. `requirements.txt`: Dependency list for running the codes
4. `training.ipynb`: Code used for training the model
5. `final_model_data.pt`: The data for the trained model, to be used for inference
6. `inference.ipynb`: Code for inference, i.e. generating labels for the unlabelled data
7. `the_crue_submission.csv`: Labels of the unlabelled data, predicted by out model
8. `Report.pdf`: Report
9. `Contribution.pdf`: Contribution file 
