# Analysis of Movie Dataset

### How I Started the Project

I've always wondered why some movies make so much money. I thought I would find answers to my questions if I analyzed their revenues with other features of the films. For this, I needed a large dataset.

[The dataset][dataset] I use for data analysis is the TMDB Dataset, which contains over 700,000 movies. There is data such as movie title, genre, original name, production companies, revenue and budget.

> **Note**
> I did not upload it to the repository due to the large file size of the dataset. You can download the latest version from the link. The version I downloaded was dated 01 October 2022.

### How I Continued the Project

I needed to prepare the found dataset for analysis. After finishing the preparations, I had to start the cleaning process. I have discarded the irrelevant columns as I will work on the questions in my mind. I have reviewed the relevant parts. I created tables comparing income with other attributes. Additionally, I tried to build a linear regression model to predict revenue.

<hr>

## Overview

### Analysis_of_Movie_Dataset.ipynb

- Preparations
- Data Cleaning
- Data Analysis
- Conclusion

### Linear_Regression.ipynb

<hr>

<table style="width:100%">
  <tr>
    <th>Languages</th>
    <td>
      <a>
        <img height="22" src="https://img.shields.io/badge/Python-1A1B27?logo=python&logoColor=3776AB&style=flat">
      </a>
      <a>
        <img height="22" src="https://img.shields.io/badge/PowerShell-1A1B27?style=for-the-badge&logo=powershell&logoColor=235391FE&style=flat">
      </a>      
    </td>
  </tr>
  <tr>
    <th>IDEs/Editors</th>
    <td>
      <a>
        <img height="22" src="https://img.shields.io/badge/Jupyter-1A1B27?logo=jupyter&logoColor=F37626&style=for-the-badge&style=flat" />
        <img height="22" src="https://img.shields.io/badge/Visual%20Studio%20Code-1A1B27?logo=visualstudiocode&logoColor=007ACC&style=flat">
      </a>
    </td>
  </tr>
  </table>
  </h5>
  </details>
  </h3>

<hr>

## Installation

`pip install jupyter notebook`

|                | Install                                |
| -------------- | -------------------------------------- |
| matplotlib     | `python -m pip install matplotlib`     |
| numpy          | `python -m pip install numpy`          |
| pandas         | `python -m pip install pandas`         |
| plotly.express | `python -m pip install plotly.express` |
| scikit-learn   | `python -m pip install scikit-learn`   |

> **Warning**
> If matplotlib=3.6.1 doesn't work, delete this version and download version 3.5.0.

`pip uninstall matplotlib`

`pip install matplotlib==3.5.0`

<hr>

## Useful Links

- [A Step-by-Step Guide to the Data Analysis Process][process-step-by-step]
- [What Is Data Cleaning and Why Does It Matter?][what-is-data-cleaning]
- [Python Pandas Tutorial: A Complete Introduction for Beginners][pandas-tutorial]
- [Learn how to use pandas inplace parameter once and for all][inplace-parameter]
- [Correlation Coefficients][correlation-coefficients]
- [Bar Chart with Plotly Express][plotly_expres-barchart]
- [Pie Charts in Python][plotly_expres-pie-charts]

<!-- Links 1 -->

[dataset]: https://www.kaggle.com/datasets/akshaypawar7/millions-of-movies

<!-- Links 2-->

[process-step-by-step]: https://careerfoundry.com/en/blog/data-analytics/the-data-analysis-process-step-by-step/
[what-is-data-cleaning]: https://careerfoundry.com/en/blog/data-analytics/what-is-data-cleaning/
[pandas-tutorial]: https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/
[inplace-parameter]: https://towardsdatascience.com/learn-how-to-use-pandas-inplace-parameter-once-and-for-all-5a29bb8bf338
[correlation-coefficients]: https://www.andrews.edu/~calkins/math/edrm611/edrm05.htm
[plotly_expres-barchart]: https://plotly.com/python/bar-charts/
[plotly_expres-pie-charts]: https://plotly.com/python/pie-charts/
