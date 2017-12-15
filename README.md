# ML2017-lab-01
Linear Regression, Linear Classification and Gradient Descent

Motivation of Experiment

Further understand of linear regression and gradient descent.
Conduct some experiments under small scale dataset.
Realize the process of optimization and adjusting parameters.
Dataset

Linear Regression uses Housing in LIBSVM Data, including 506 samples and each sample has 13 features. You are expected to download scaled edition. After downloading, you are supposed to divide it into training set, validation set. 
Linear classification uses australian in LIBSVM Data, including 690 samples and each sample has 14 features. You are expected to download scaled edition. After downloading, you are supposed to divide it into training set, validation set.

Environment for Experiment

python3, at least including following python package: sklearn，numpy，jupyter，matplotlib 
It is recommended to install anaconda3 directly, which has built-in python package above.

Time and Place

2017-12-02 9:00-12:00 AM B7-138/238

Submit Deadline

2017-12-08 12:00 noon

Experiment Form

Complete Independently.

Experiment Step

The experimental code and drawing are completed on jupyter.

Linear Regression and Gradient Descent

Load the experiment data. You can use load_svmlight_file function in sklearn library.
Devide dataset. You should divide dataset into training set and validation set using train_test_split function. Test set is not required in this experiment.
Initialize linear model parameters. You can choose to set all parameter into zero, initialize it randomly or with normal distribution.
Choose loss function and derivation: Find more detail in PPT.
Calculate gradient  toward loss function from all samples.
Denote the opposite direction of gradient  as .
Update model: .  is learning rate, a hyper-parameter that we can adjust.
Get the loss  under the training set and  by validating under validation set.
Repeate step 5 to 8 for several times, and drawing graph of  as well as  with the number of iterations.
Linear Classification and Gradient Descent

Load the experiment data.
Divide dataset into training set and validation set.
Initialize SVM model parameters. You can choose to set all parameter into zero, initialize it randomly or with normal distribution.
Choose loss function and derivation: Find more detail in PPT.
Calculate gradient  toward loss function from all samples.
Denote the opposite direction of gradient  as .
Update model: .  is learning rate, a hyper-parameter that we can adjust.
Select the appropriate threshold, mark the sample whose predict scores greater than the threshold as positive, on the contrary as negative. Get the loss  under the trainin set and  by validating under validation set.
Repeate step 5 to 8 for several times, and drawing graph of  as well as  with the number of iterations.
Finishing experiment report according to result: The template of report can be found in example repository.
