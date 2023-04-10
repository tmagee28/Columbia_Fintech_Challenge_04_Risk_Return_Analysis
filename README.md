# Columbia_Fintech_Challenge_04_Risk_Return_Analysis



## Description

In this challenge, we assume the role of a quantitative analyst aiming to evaluate new investment options for inclusion into client's portfolios.  In this excercise, four funds as well as the S&P 500 are analyzed over the timeframe 2014-10-01 through 2020-09-11. The four funds analyzed include: Soros Fund Management LLC, Paulson & Co Inc, Tiger Global Management LLC and Berkshire Hathaway Inc. The DataSet, ```whale_navs.csv```, is located in the Resources folder in the project repository.

By analyzing the key risk-managment metrics: the daily returns, standard deviations, Sharpe Ratios, and betas, we will recommend one of the funds to be included into the firm's suite of fund offerings. 

The sections in the JupyterLab notebook include: 

1. Import the Data

2. Analyze the Performance

3. Analyze the Volatility

4. Analyze the Risk

5. Analyze the Risk-Return Profile


---

## Technologies

This project leverages JupyterLab Version 3.0.14 in association with Anaconda distribution and the Conda package manager.  The following packages are also used: 

* [pandas](https://github.com/pandas-dev/pandas) - For the current source code hosted on GitHub.


## Installation Guide

The dependencies used are included when using Anaconda distribution and Conda package manager to manage the Python environment.  No additional installations are required.

### Imported Libraries and Dependencies

```python
   import pandas as pd
   from pathlib import Path
   %matplotlib inline
```


---
## **Contributors**

### **Author**

Tommy Magee
[LinkedIn](https://www.linkedin.com/in/thomas-magee-2009a72a/)



### **BootCamp lead instructor**

Vinicio De Sola


---

## License

MIT License

Copyright (c) [2022] [Thomas 'Tommy' Magee]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

