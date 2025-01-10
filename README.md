Predicting Bike Share Demand with AutoGluon


Create a kaggle account if you do not have one and download the bike sharin dataset and train a model using AutoGluon, and submit your results for an initial ranking.

After completing the first workflow, we iterate on the process by trying to improve the score. This is accomplished by adding more features to the dataset and tuning some of the hyperparameters available with AutoGluon.

Finally we submit all our work and write a report detailing which methods provided the best score improvement and why. A template of the report can be found here.

To meet specifications, the project will require at least these files:

    Jupyter notebook with code run to completion
    HTML export of the jupyter notebbook
    Markdown or PDF file of the report

Images or additional files needed to make your notebook or report complete can be also added.
Getting Started

    Clone this template repository git clone git@github.com:udacity/nd009t-c1-intro-to-ml-project-starter.git into AWS Sagemaker Studio (or local development).

sagemaker-studio-git1.png

sagemaker-studio-git2.png

    Proceed with the project within the jupyter notebook.
    Visit the Kaggle Bike Sharing Demand Competition page. There you will see the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. You will primarily be focused on the data and ranking sections.

Dependencies

Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 

Installation

For this project, it is highly recommended to use Sagemaker Studio from the course provided AWS workspace. This will simplify much of the installation needed to get started.

For local development, you will need to setup a jupyter lab instance.

    Follow the jupyter install link for best practices to install and start a jupyter lab instance.
    If you have a python virtual environment already installed you can just pip install it.

pip install jupyterlab

Project Instructions

    Create an account with Kaggle.
    Download the Kaggle dataset using the kaggle python library.
    Train a model using AutoGluon’s Tabular Prediction and submit predictions to Kaggle for ranking.
    Use Pandas to do some exploratory analysis and create a new feature, saving new versions of the train and test dataset.
    Rerun the model and submit the new predictions for ranking.
    Tune at least 3 different hyperparameters from AutoGluon and resubmit predictions to rank higher on Kaggle.
    Write up a report on how improvements (or not) were made by either creating additional features or tuning hyperparameters, and why you think one or the other is the best approach to invest more time in.


