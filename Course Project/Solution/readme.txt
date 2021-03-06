# requirements

python == 3.7
numpy == 1.21.2
pandas == 1.3.4
matplotlib == 3.5.0
seaborn == 0.11.2
scikit-learn == 1.0.1

# directory structure

|- project
	|- figs
	|- res
	|- dataset
		|- algerian_fires_test.csv
		|- algerian_fires_train.csv
	|- main.ipynb
	|- model.py
	|- readme.txt
	|- utils.py

# run

We write the main code in the main.ipynb, where you can see and directly run this file to reproduce our results. And we implement baseline method and trivial method in the model.py. In utils.py, we implement some useful and common function to avoid repeated define them. The figures generated by the program are stored in the figs directory, and the results and their corresponding parameters are stored in the res directory. In this directory, each csv file represents the parameters set of an algorithm, like support vector machine or others.