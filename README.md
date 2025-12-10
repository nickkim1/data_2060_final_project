### Data2060 Final Project (All Pairs, One vs. All)
Authors: Nicolas Kim (nicolas_kim@brown.edu), Adam Ibrahim (adam_ibrahim@brown.edu), Erin Okey (erin_okey@brown.edu)

This is our group's final project on implementing the one-vs-all and the all-pairs algorithms from Lecture 5. As our base learner for both algorithms, we use the binary logistic regression model we implemented in HW4. The final_project.ipynb file contains the analysis including unit tests, integration tests against sklearn, and the core model implementation. To run this assignment:

0. First note that these are the package versions utilized in the project:
```
- python = version 3.12.11
- matplotlib = version 3.10.5
- pandas = version 2.3.2
- scikit-learn = version 1.7.1
- numpy = version 2.3.2
- jupyter
- pytest = version 8.4.1
```

1. Setup environment per the YAML file in the root directory. To do so, run
the following command in the terminal.
```
conda env create -f env.yml
```

1. Open the notebook, setting the kernel to the data2060_final_project_env environment you just created in Conda. 
2. Run the environment checks to make sure your environment dependencies are as expected.
3. Run the other cells in the notebook, one by one.

Enjoy!