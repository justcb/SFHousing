# San Francisco Housing Analysis


---

## Technologies

This application runs in a Jupyter Notebook.  

It imports pandas, hvplot.pandas, and Path from pathlib.

---

## Installation Guide

No installation is required, other than loading in Jupyter Notebook.  To do so, navigate to the directory containing the notebook in terminal or GitBash.  There, type `jupyter lab`.  Then, on the right side of the notebook click on san_francisco_housing.ipynb

This file requires the housing data file that is included in Resources.  The file, "sfo_neighborhoods_census_data.csv" is read in to create the dataframe.

---

## Usage

Initially, the notebook imports the required libraries.

![](/img/1.png)

Next, after reading in the data, the data is grouped by year and presented in a table.

![](/img/2.png)

The data is presented graphically to demonstrate the growth in the number of housing units available in San Francisco from 2010 to 2016.

![](/img/3.png)

Next, the cumulative sales price per square foot data is displayed along with the gross rent data to show the varying growth rates for these two important real estate measures.

![](/img/4.png)

The data is then granularized and provided on a neighborhood by neighborhood basis.

![](/img/5.png)

Finally, the data is shown on a map of San Francisco that shows the sale price per square foot and the gross rent for various neighborhoods across the city.

![](/img/6.png)

---

## Contributors

This project was created as a part of the Rice FinTech Bootcamp.

---

## License

This software is licensed for use under the included MIT License.
