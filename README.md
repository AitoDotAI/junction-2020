# junction-2020

In this repository you can find the Jupyter Notebook, which has the Python code how to modify the [Kaggle dataset Restaurant data with consumer ratings](https://www.kaggle.com/uciml/restaurant-data-with-consumer-ratings) to create a database in Aito. You will need Python 3.6 or higher to run the code.

1. Clone the repository with `git clone git@github.com:AitoDotAI/junction-2020.git` 

2. In the repo directory, create a directory `data` and subdirectory under it called `original`, download the Kaggle dataset files to the `original` directory. 

3. Install Jupyter Notebook with `pip install jupyterlab`, you can then run the notebook with the command `jupyter notebook` (run it in the directory where you have the .ipynb notebook). The browser will open and you can now double click on the `restaurant_recomender.ipynb`, it will open the IDE.

4. After you have added your Aito instance URL and read/write API key to the Notebook code (variables AITO_INSTANCE_URL and AITO_API_KEY), run the code from the forward button on top and the code will upload the dataset into you Aito instance. 

You can find a couple of query examples in the end of the notebook. Good luck with the challenge!
