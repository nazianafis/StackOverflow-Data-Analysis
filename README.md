# StackOverflow-Data-Analysis
Every year since 2011, Stack Overflow has been conducting a survey to understand its user base in particular and the global IT scenario in general. The 2020 results have recently been released. With some basic data exploration tactics on answers given by survey respondents, I was able to unveil interesting insights.


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I used _Stack Overflow Annual Developer Survey 2020_ data in order to answer the following three questions:

1. Which country provides the highest job satisfaction for developers?
2. Is there a difference in job satisfaction between developers who had an IT related undergraduate major and those who didn’t?
3. Do developers from Non IT backgrounds think differently about the importance of having a formal education, such as a university degree in Computer Science, for their career?

The complete set of files is publicly available and can be downloaded from the Stack Overflow site [here](https://insights.stackoverflow.com/survey).  Alternatively, you can find the main CSV file (titled _survey_results_public.csv_) in my Github repo [here](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/survey_results_public.csv).

![stack overflow image](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/images/so-1%20(2).png)


## File Description <a name="files"></a>

* One Jupyter notebook: The main showcase of work related to the above questions.
* One CSV file: Dataset downloaded from the Stack Overflow website.

## Results<a name="results"></a>

Here is a quick summary of the analysis: (An in-depth report can be found on my Medium blog [here](https://nazianafis.medium.com/best-country-to-work-in-2020-15a790b00904).)
##### 1. I measured job satisfaction levels for each country and found that Sweden topped the charts. United States stood second and Netherlands third.

![first answer](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/images/graph-1.png)

##### 2. Then, I looked at undergraduate majors and found that developers from ‘Non IT related’ backgrounds had better job satisfaction.

![second answer 1](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/images/graph-2.png)

![second answer 2](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/images/graph-4.png)

##### 3. At last, I found that developers from ‘Non IT related’ fields were also the ones who believed that having a formal education, such as a degree in Computer Science, was not as important for their career. This is also backed up by the fact that despite not having a background in IT, these respondents are not only working as developers but also have higher job satisfaction in their work.

![third answer](https://github.com/nazianafis/StackOverflow-Data-Analysis/blob/main/images/graph-3.png)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The dataset Stack Overflow Developer Survey Results 2020 is made available by [Stack Overflow](https://insights.stackoverflow.com/survey) under the Open Database License [ODbL](http://opendatacommons.org/licenses/odbl/1.0/).
Any rights in individual contents of the database are licensed under the [Database Contents License](http://opendatacommons.org/licenses/dbcl/1.0/)
