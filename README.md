# StackOverflow-Data-Analysis

## Table of Contents

1. [Overview](#overview)
2. [Getting Started](#getting-started)
    1. [Dependencies](#dependencies)
    2. [Installation](#installation)
3. [Project Motivation](#project-motivation)
4. [Results](#results)
3. [Author](#author)
4. [Licensing](#licensing)

## Overview <a name="overview"></a>
Every year since 2011, Stack Overflow has been conducting a survey to understand its user base in particular and the global IT scenario in general. The 2020 results have recently been released. With some basic data exploration techniques on answers given by survey respondents, I was able to unveil interesting insights.

## Getting Started <a name="getting-started"></a>

### Dependencies <a name="dependencies"></a>
* Python 3.*
* Libraries: Pandas, Seaborn, Matplotlib
* Google Colaboratory

### Installation <a name="installation"></a>

* Datasets: The complete set of files is publicly available and can be downloaded from the Stack Overflow site [here](https://insights.stackoverflow.com/survey).  Alternatively, you can find the main CSV file (titled _survey_results_public.csv_) in my Github repository [here](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/survey_results_public.csv).
* Others: The code can be run in [Google Colab](https://colab.research.google.com/drive/1Xqh_Obd0xeg8yzp6U-KrVHLqiAan-Hqr) as an Interactive Python Notebook (ipynb). No additional installation is required.
    - Colaboratory allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer (other than a browser).

### Project Motivation <a name="project-motivation"></a>

For this project, I used _Stack Overflow Annual Developer Survey 2020_ data in order to answer the following three questions:

1. Which country provides the highest job satisfaction for developers?
2. Is there a difference in job satisfaction between developers who had an IT related undergraduate major and those who didn’t?
3. Do developers from Non IT backgrounds think differently about the importance of having a formal education, such as a university degree in Computer Science, for their career?

![stack overflow image](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/screenshots/so-1%20(2).png)

## Results<a name="results"></a>

Here is a quick summary of the analysis: (An in depth report can be found on my Medium blog [here](https://nazianafis.medium.com/best-country-to-work-in-2020-15a790b00904).)
##### 1. I measured job satisfaction levels for each country and found that Sweden topped the charts. United States stood second and Netherlands third.

![first answer](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/screenshots/graph-1.png)

##### 2. Then, I looked at undergraduate majors and found that developers from ‘Non IT related’ backgrounds had better job satisfaction.

![second answer 1](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/screenshots/graph-2.png)

![second answer 2](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/screenshots/graph-4.png)

##### 3. At last, I found that developers from ‘Non IT related’ fields were also the ones who believed that having a formal education, such as a degree in Computer Science, was not as important for their career. This is also backed up by the fact that despite not having a background in IT, these respondents are not only working as developers but also have higher job satisfaction in their work.

![third answer](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/screenshots/graph-3.png)

## Author<a name="author"></a>
* [Nazia N.](https://github.com/nazianafis)

## Licensing<a name="licensing"></a>

* The dataset Stack Overflow Developer Survey Results 2020 is made available by [Stack Overflow](https://insights.stackoverflow.com/survey) under the Open Database License [ODbL](http://opendatacommons.org/licenses/odbl/1.0/).
* Any rights in individual contents of the database are licensed under the [Database Contents License](http://opendatacommons.org/licenses/dbcl/1.0/).
