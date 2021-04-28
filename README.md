# nlu-second-assignment
Repository with code and explanations as well as miscellaneous material - 2nd Assignment of the Natural Language Understanding course at University of Trento, MSc in Artificial Intelligence Systems


## Repository Structure  
The content of the repository is organized as shown in the snippet below.
```
nlu-second-assignment
|── data/
    |── conll2003/ (dataset provided for the assignment)
        |── train.txt
        |── test.txt
        |── dev.txt
        
|── src/
    |── conll.py (provided conll fns for the assignment)
    
|── main.ipynb (notebook containing the tasks of the assignment)
|── README.md (this file)
|── .gitignore
|── requirements.txt (frozen python requirements for this repo)
```  

Since I've made use of a Jupyter Notebook, there is no external report. Instead, every code cell in the .ipynb file is preceded by a Mardown cell that describes the implemented logic and, thus, plays the role of the report.  
  
The notebook that contains both code and explanations is **main.ipynb**.

## Requirements and dependencies
In **main.ipynb** an introductory section is dedicated to guide readers through the installation process. Please note that in order to open up a notebook in your browser, you must have `jupyter` installed:  
```
$ pip install jupyter
```  
To quickly install **every** dependency of the repo (incl. jupyter), run:  
```
$ pip install -r requirements.txt
```   

### Notes on installation and runtime  
The content of this repository has been tested under the **Python 3.9** interpreter inside an Anaconda Virtual Environment. External libraries are intended to be installed with **pip**, version 21.0.1.
