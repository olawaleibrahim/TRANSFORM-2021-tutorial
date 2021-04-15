# TRANSFORM-2021-tutorial: Big Data Lithology Prediction

The tutorial is on prediction of lithofacies from well log data. It makes use of data from the FORCE 2020 lithology prediction competition.
It covers the following:

* Data Visualization and Exploratory Data ANalysis
* Data Preparation
* Model Training and Prediction
* Model Evaluation
* Model Performance Improvement with different techniques
    * Data Augmentation
    * Cross validation technique
    * Model regularization for better training (for slower weight decay)

It also covers key things to watch out for when working with big subsurface data  like;

* Selecting a proper cross validation technique helps in making more confident decisions
* Preventing overfitting by;
    * Creating different validations sets (give "whys" on choice of method for creating them)
    * Making proper evaluations on validation sets with different metrics

Train data missing from repo is available in the following drive link: [train data] (https://drive.google.com/drive/folders/1x_Vpt_EsNXVVY0gl_qjUJzLOfSQSLz5M?usp=sharing) 

#### Licensing #### 
Copyright 2020 Olawale Ibrahim

This work is open source:

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Text is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"> CC BY 4.0 Creative Commons License</a>.

Code is Licensed under the [Apache License, Version 2.0]( http://www.apache.org/licenses/LICENSE-2.0)

The well log labels used in this repo are licensed CC-BY-4.0.  The well log data used in this repo is licensed as [Norwegian License for Open Government Data (NLOD) 2.0](https://data.norge.no/nlod/en/2.0/).  Lithofacies data was provided by the FORCE Machine Learning competition with well logs and seismic 2020. Bormann P., Aursand P., Dilib F., Dischington P., Manral S. 2020. [2020 FORCE Machine Learning Contest](https://github.com/bolgebrygg/Force-2020-Machine-Learning-competition)