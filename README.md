# forecasting_net_prophet
This is a Python-Jupyter notebook that contains data preparation, analysis, and visualizations for time series data. Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company. An evaluation of how the company’s stock price correlates to its Google Search traffic. A Prophet forecast model that can predict hourly user search traffic. (Optional) A plot of a forecast for the company’s future revenue



## Technologies

This project leverages python 3.7 with the following packages:

* [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/#) - Is a browser-based interface to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.

* [google colab](https://colab.research.google.com/) - Colab, or "Colaboratory", allows you to write and execute Python in your browser, with Zero configuration required, Access to GPUs free of charge, Easy sharing.

* [prophet](https://facebook.github.io/prophet/docs/quick_start.html#python-api) - Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

---

## Installation Guide

You will need Python version 3.7 or above and gitbash/terminal on your computer, along with other supporting packages as mentioned below. 

Please follow instructions from the below link to install python 3.7 or above on your computer

[To install Python, follow instructions from this link](https://www.python.org/downloads/)

[To install Git Bash, follow instructions from this link](https://github.com/git-guides/install-git)


To access the Jupiter notebook, first install the following dependencies.

 [Anaconda](https://docs.anaconda.com/anaconda/install/)

```python
# install conda dev environment and activate it
    conda update conda
    conda create -n dev python=3.7 anaconda
    conda activate dev
# install Jupyter Lab
    pip install jupyterlab


```


---


## Usage

To use the Jupyter Notebook, clone the repository and do not forget to run the above commands as applicable,

```git
git clone https://github.com/sidbetatester/forecasting_net_prophet
```

Upload the Jypyter notebook 'forecasting_net_prophet.ipynb' file from github or your system to google colab, you will notice an interface similar to Jypyter lab, and you will have the complete analysis including the modules that need to be installed within google colab. 


Note:
* You can shut down the notebook by closing the browser.


## Contributors

Siddharth Venkumahanti
[linkedin](https://www.linkedin.com/in/siddharthvenkumahanti/)


---


## License

### MIT License

Copyright (c) [2022] [Siddharth Venkumahanti]

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

![MIT License](Images/MIT_License.png)