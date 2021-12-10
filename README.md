# Machine-conditions-monitoring -- Unsupervised 
To give a brief itroduction of this project you can refer to the description below.
- `Deployment strategy` :
  - GitHub page
  - PowerPoint
  - Jupyter Notebook

***
### Description
This is a solo project to label the machines as normal and abnormal using the clustering models.
We have implemented clustering models that we learnt in our BeCode Machine learning module.

We tried to use different models for each machine and arrive at a good machine learning model that predicts the labelling of a sound wave- whether it is normal or abnormal.

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

Consists of all the clustering models for each machine as a jupyter notebook.
Also the datasets for all machines with all the features are included in the dataset folder.

#### requirements.txt 

- Gives all the required libraries to run this code.

***
### Usage
- Once you have all the libraries successfully installed you can open and run each model to get the output
    ```javascript
    jupyter notebook
    ```

***
### Visuals
![Clustering PUMP machine using K-means algorithm](https://github.com/Arfameher/machine_conditions-unsupervised/blob/main/images/clustering_pump_kmeans.png
)

![Clustering PUMP machine using DBSCAN algorithm](https://github.com/Arfameher/machine_conditions-unsupervised/blob/main/images/clustering_pump_DBSCAN.png)

***
### References
This is the link we used to download our dataset of sound files for normal and abnormal of all the four machines - Valve, Pump, Fan, Slider.

https://zenodo.org/record/3384388#.YFIrNXnvJEY

This documentation was quite helpful in understanding the data. https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53


***
### Contributors
There are no contributors as of now, this is a solo project. If you wish to contribute to this repo, you are Welcome!
You can clone this repository and create a new branch and push your changes.

***
### Timeline
Dec 2021

Time limit: 3 days --> 8/12/2021 - 10/12/2021 

This is a solo project given to us at [BeCode](https://becode.org/) after completion of our study material related to data science libraries. I have used `pandas`, `numpy`, `matplotlib` ad `librosa`
The time that I took to finish this project was 3 days as we had done a part of this project earlier as a team.
Link to the other repository is here 
https://github.com/UjjwalKandel2000/Machine-conditions-monitoring

***
### Personaal Situation
This is a personal project given to me at [BeCode](https://becode.org/)
I am currently aspiring to be a Data Scientist. This is to develop a clustering model for all the machines to label the sounds.

Here is how you can contact me :

LinkedIn : [Arfameher](https://www.linkedin.com/in/arfa-meher/)  
Email : arfaameher@outlook.com
