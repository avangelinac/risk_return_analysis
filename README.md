# risk_return_analysis
module_four_challenge

Given four investment funds and the S&P 500 index, this program will determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

---
## Technologies
Code is written using Python version 3.7 and runs in a Jupyter Lab notebook. The following libraries are required to run the code:
```python
import pandas as pd
from pathlib import Path
import numpy as np

%matplotlib inline
```

---
## Installation Guide
Using the command prompt, navigate to an empty folder where you would like to install the files and type the command:
```
git clone https://github.com/avangelinac/risk_return_analysis.git
```
Then, navigate to the newly created folder:
```
cd risk_return_analysis
```
Finally, launch Jupyter Lab by typing the following command:
```
jupyter lab
```
**Note: You must install Jupyter Lab in your Conda environment in order to run this program.**

See the [Jupyter Lab Installation Guide](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) for more information.

---
## Usage
The program will import NAV prices from four portfolios and closing price of the S&P 500 Index. Then, performance of the four portfolios will be compared to the broader stock market, represented by the S&P 500. Volatility is measured by plotting the daily return values. Risk assessment is made by plotting the 21 day rolling standard deviations of the four funds and comparing to the S&P 500. Risk-return ratios are analyzed by calculating the Sharpe Ratios of each fund and the S&P 500. Lastly, portfolio diversification is optimized by calculating and analyzing the 60-day rolling beta values for two different funds correlated with the S&P 500.

---
## Examples
![Daily Return Values - Berkshire Hathaway vs. S&P 500](/Images/ex_1.png)
![Daily Return Values - Box Plot](/Images/ex_2.png)
![Cumulative Daily Returns - Berkshire Hathaway vs. S&P 500](/Images/ex_3.png)
![Rolling Standard Deviations - All](/Images/ex_4.png)
![Rolling Standard Deviations - Four Funds](/Images/ex_5.png)
![Sharpe Ratios](/Images/ex_6.png)
![Rolling Betas](/Images/ex_7.png)

---
## Contributors
Open source with initial contributions by Avangelina Cazares.

---
## License

None