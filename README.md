# TV-script-generator
This project is a part of Udacity's Deep learning course: Recurrent Neural Networks(RNN)

The purpose of this project for the students(me) to be able to implement Long Short Term Memory (LSTM) by themselves. We will be training the model on (Seinfeld TV scripts)[https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv] and generate a new script from it. One of the passing criteria is to train until the training loss falls below 3.5.


## Files included
* dlnd_tv_script_generation.ipynb - this will be the main file
* helper.py - it contains helper function, such as save function
* problem_unittests.py - this was used by the project reviewer as criteria to check the project.
* workspace_utils.py - this file is used to keep Udacity's workspace awake while training.

## Installation
* To use this on your local system - install (miniconda)[https://docs.conda.io/en/latest/miniconda.html]

* Open **Anaconda prompt** and install git:

  ``` conda install git ```

* Clone the repository and navigate to the folder.

  ``` git clone https://github.com/PwMarkLiu/TV-script-generator.git ```

* Create a new environment `deep-learning`
  - for Windows:
``` 
    conda create --name deep-learning python=3.6
    activate deep-learning 
```

* Install PyTorch and torchvision;
  - for Windows:
```
    conda install pytorch -c pytorch
    pip install torchvision
```

* Install pip packages in the `requirement.txt`
```
    pip install -r requirements.txt
```

* You can now navigate to the notebook and start using it.

