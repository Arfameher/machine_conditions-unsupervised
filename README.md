# Machine-conditions-monitoring
To give a brief itroduction of this project you can refer to the description below.
- `Deployment strategy` :
  - GitHub page
  - PowerPoint
  - Jupyter Notebook

***
### Description
This is a group project to check whether the machines working have an abnormal sound being produced and need maintenance.
We have implemented classification models that we learnt in our BeCode Machine learning module.

We tried to use different models for each machine and arrive at a good machine learning model that predicts the abnormality of a machine using the sound wave given as input.

***
### Installation
Before running this code you need to have anaconda installed in your system and jupyter notebook running with basic libraries.

To run this code you have to clone the repository or download it as a zip file and run it. But before that we need to install some libraries to run this code.

- Create virtual environment to run this code. 
    - If you are using anaconda --> `conda create -n <yourenvname> python=x.x anaconda`
    - Activate your virtual environment -->
    `conda activate <yourenvname>`

- The library that we have used to read a sound file is `librosa`. It loads the data from a sound file and also extracts the particular features using which we can predict a model for the machines. All these libraries are written in reuirements.txt file.
To install all these libraries do the folling steps:

    1. cd to the directory where `requirements.txt` is located
    2. run the command in your shell: 
        ```javascript
        pip install -r requirements.txt
        ``` 
***
### Repo Architecture


#### requirements.txt 

- Gives all the required libraries to run thiss code.

***
### Usage
- Once you have all the libraries successfully installed you can open and run each model to get the output
    ```javascript
    jupyter notebook
    ```

***
### Visuals

***
### References
This is the link we used to download our dataset of sound files for normal and abnormal of all the four machines - Valve, Pump, Fan, Slider.

https://zenodo.org/record/3384388#.YFIrNXnvJEY

This documentation was quite helpful in understanding the data. https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53


***
### Contributors
This project is worked-out by the following team:

- [Arfameher](https://github.com/Arfameher)                                                                                    
- [Ujjwal Kandel](https://github.com/UjjwalKandel2000) 
If you wish to contribute to this repo, you are Welcome!
You can clone this repository and create a new branch and push your changes.

***
### Timeline
Nov - Dec 2021

Time limit: 1 week --> 29/11/2021 - 3/12/2021 

This is a group project given to us at [BeCode](https://becode.org/) after completion of our study material related to Machine Learning models. I have used `pandas`, `numpy`, `librosa`, `pickle` and `scikit learn`.
The time that we took to finish this project was a week. If given more time we could improve our model and take input from the user and predict if abnormal or not.

***
### Personal Situation
This is a group project given to us at [BeCode](https://becode.org/)

Here is how you can contact us :

LinkedIn : [Arfa Meher](https://www.linkedin.com/in/arfa-meher/)

[Ujjwal Kandel](https://www.linkedin.com/in/ujjwal-kandel-10743a1bb/)

Email : 

arfaameher@outlook.com

ujjwalkandel2000@gmail.com
