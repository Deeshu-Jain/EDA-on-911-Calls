# EDA-on-911-Calls


## What is Exploratory Data Analysis(EDA)?
**EDA** means trying to understand the given data much better, so that we can make some sense out of it.

![Cover](assets/cover.jpg)

In statistics, exploratory data analysis is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task :wink:.
You can find a more formal definition on [Wikipedia](https://en.wikipedia.org/wiki/Exploratory_data_analysis).


## About Dataset - 911 Calls

### Dataset Description
This file contains **calls to 911 (emergency calls)** in Montgomery County Pennsylvania. The data contains the following fields:

- *lat* : String variable, Latitude
- *lng*: String variable, Longitude
- *desc*: String variable, Description of the Emergency Call
- *zip*: String variable, Zipcode
- *title*: String variable, Title
- *timeStamp*: String variable, YYYY-MM-DD HH:MM:SS
- *twp*: String variable, Township
- *addr*: String variable, Address
- *e*: String variable, Dummy variable (always 1)

The dataset is available publicly on *Kaggle* Website. You can access or download the dataset from [here](https://www.kaggle.com/datasets/mchirico/montcoalert).


## Content
**US Accidents(2016-2021) Dataset - EDA:**  Exploratory Data Analysis of the accidents occured in differents streets, cities, states of US. The weather conditions at the most of the time of the accidents, the severity, time analysis all of these things are analysed and visualized in this notebook. Some important insights are also derived based on the data visualization.


## Instructions for Running Python Notebooks Locally
 
 - Install the required libraries in your Virtual Environment.

 - Run notebooks as usual by using a jupyter notebook server, Vscode etc.


## Libraries to Install
    
:white_check_mark: **Numpy** : [Numpy Installation](https://numpy.org/install/)

:white_check_mark: **Pandas** : [Pandas Installation](https://pandas.pydata.org/docs/getting_started/index.html)

:white_check_mark: **Matplotlib** : [Matplotlib Installation](https://matplotlib.org/stable/users/getting_started/)

:white_check_mark: **Seaborn** : [Seaborn Installation](https://seaborn.pydata.org/installing.html)



## Project Notebook

You can install Jupyter Notebook Environment from [here](https://jupyter.org/install) or through the [Anaconda Distribution](https://www.anaconda.com/products/distribution) or, can even use any IDE you like.

You can access the **Project Notebook** from [here](https://github.com/Deeshu-Jain/EDA-on-911-Calls/blob/main/EDA%20on%20911%20Calls.ipynb).


## Code Snippet

```python
df[df['Reason']=='Traffic'].groupby('Date').count()['twp'].plot()
plt.title('Traffic')
plt.tight_layout()
```


## Screenshots
Includes Screenshots of Some Visualization Figures/Plots

![Demo1](assets/ss1.png)


![Demo2](assets/ss2.png)


## Support My Work :wink:
You can feel free to comment on my projects, find the bugs :mag_right: or tell me what your thoughts about my coding, analysis and insight. You can also take some codes away if you think some of them can be useful for your projects :computer:. 
If you liked what you saw :blush:, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot :gun: an email at djjain844@gmail.com.

You can check out my portfolio here :v:.
