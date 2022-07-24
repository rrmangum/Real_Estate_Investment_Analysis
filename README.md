# Real Estate Investment Analysis For A Proptech Company in San Francisco

This analysis uses data aggregation and visualization techniques to consider potential investments in the San Francsico real estate market.

![San_Francisco_Sale_Rent.png](https://github.com/rrmangum/Real_Estate_Investment_Analysis/blob/main/images/avg-sale-px-sq-foot-gross-rent.png?raw=true)

---

## San Francisco Neighborhood Map by Gross Rent

![Geo_Plot.png](https://github.com/rrmangum/Real_Estate_Investment_Analysis/blob/main/images/6-4-geoviews-plot.png?raw=true)

---

## Technologies

This analysis uses python Python 3.9.12 and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides the calculating functions, and data manipulation necessary to conduct this analysis.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - Provides the path to a CSV database.
* [hvplot](https://hvplot.holoviz.org/user_guide/index.html) - Provides the visualizations.

---

## Installation Guide

An installation is not required for this analysis if you are only wanting to review the analysis. If you wish to alter the inputted values, follow the steps below:

1. Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. In your terminal or gitbash, navigate to the directory you saved the analysis files. Enter the following command:

```python
jupyter lab
```
2. To install hvplot, in your terminal or gitbash enter the following command:

```python
conda install -c pyviz hvplot geoviews
```

---

## Usage

This analysis is not meant as financial advice, and is purely a comparison of home sale price against rental income in the San Francisco real estate market from 2010-2016.

---

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

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
