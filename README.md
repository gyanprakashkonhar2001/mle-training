enh/#1/first_branch
# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To excute the script
python < scriptname.py >
=======
# mle-training

After confirming that you created the environment, you can now actually use it. We can accomplish this by typing (assuming your environment is underneath your base):

**$ conda activate your_env_name**

At this point, your terminal prompt should look something like this:

**(your_env_name) Your_Machine:your_directory username$**

If that command doesn’t result in a similar output for whatever reason,
you can specify the full path by typing in something similar to the command below:

**$ conda activate /Users/your_username/anaconda3/envs/your_env_name**

If, like me, you want to know exactly what is happening when you type in the word ‘activate’, it runs a bash script that exists within a subdirectory of the environment.
In my case, the filepath to the script looked something like:

**$ /Users/my_username/anaconda3/envs/my_env_name/lib/python3.6/venv/scripts/common/activate**
To stop using the environment, type in

**$ conda deactivate**

In a similar fashion to the activate command, the deactivate command runs a function from the activate bash script.

If you would like to update the environment, type in:

**$ conda env update –f environment.yml –n your_env_name**

If you would like to get rid of the entire environment, merely type in:

**$ conda remove --name your_env_name --all**

The ‘ — all’ flag is to remove all packages from the environment and
is necessary to completely clean the environment.
 main
