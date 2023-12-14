# Recommender Systems in Data Mining
### Course: DSC 210: Numerical Linear Algebra
Instructor: Dr. Tsui-wei Weng

Group: Xujun Lian, David Tu, Albert Zhong

## Instructions
Ensure that the following libraries are installed in python 3 environment:
- surprise (the notebook will do this for you, if not)
- pandas
- numpy
- fastai

Open `mf_ncf_collaborative_filtering.ipynb` and follow the instructions in there while running all the cells of the notebook.

The only thing to note is that before you run the cells, you will need to download the dataset and unzip it into the same directory as the notebook. In other words, the CSV files inside the ZIP file should live in the same directory as the notebook, in order for the notebook to read the `ratings.csv` file. The dataset is also here zipped up in the GitHub repo as `ml-latest-small.zip`, so you can download that as well.

## Results
You will get lots of different results based on the different hyperparameters set for each of the models. Below is a chart of our findings of the most optimal algorithms, that is, the errors that are the least over/underfitted and lowest for a given technique.
![Result](https://github.com/r2dtu/210finalproject/blob/main/results.png)
