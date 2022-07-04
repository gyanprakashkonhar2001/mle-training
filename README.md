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
