## SEEGVIS

### Introduction

**It is a web system for visualizing and processing EEG/SEEG FC (Functional Connectivity) data.**

##### Methodological Techniques:

1. Non-linear regression (Piecewise linear regression )
2. Sliding windows and max time lag
3. Anomaly detection and handling

##### Project Techniques:

1. Flask
2. Vue.js
3. D3.js

##### Visualization:

1. line chart
2. box chart
3. violin chart
4. heat map
5. theme river / stream graph
6. 3-D scatter chart

### Deployment

1. Install [Miniconda](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/) 

   For Windows 64, click [here](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/) to download installation package, then install it.

2. Use conda to create an environment with python3.7

   `conda create -n seegvis python=3.7`

3. Activate this environment

   `conda activate seegvis`

4. Install those python packages:

   `pip install flask scipy pandas xlwt` 

   you can use image sources to speed up installation, like:

   `pip install -i https://pypi.tuna.tsinghua.edu.cn/simple flask scipy pandas xlwt` 

5. Enter the SEEGVIS project folder, then run it:

   `python app.py`

   now the project is running on your [localhost](http://localhost)