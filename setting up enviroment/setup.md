## ` 1. ` Setting up Conda Environment 


### ` 1.1 ` Downloading and install
First of all you need to go to the Anaconda website and download and install the anaconda software
[Anaconda website](https://www.anaconda.com)

### ` 1.2 ` Setting up the Environment
Create a folder where you will be saving all your ML work. For me I will be using the location `C:data\ML`
Now open up the anaconda prompt which will be available by searching in the start menu on windows or by searching.

When we open a new prompt change directories to your project folder and run the below lines.

`conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter seaborn`
This line will create an environment of the name `env` and install the python packages 
* Pandas
* Numpy 
* Matplotlib 
* Scikit-learn 
* Jupyter Notebook
* Seaborn

### ` 1.3 ` Activating the Environment
To activate the environment you can simply write conda followed by activate and then the full path of the directory and then the name of environment

` conda activate C:\data\ML\env `

### ` 1.4 ` Deactivating the Environment
To deactivate your environment simply type conda deactivate
` conda deactivate `

### ` 1.5 ` List all your Environments
To list and view all your environment use the line below
` conda env list `
