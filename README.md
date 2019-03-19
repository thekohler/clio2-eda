Michael Kohler

# Exploratory data analysis assignment

For this assignment you should follow these steps.

1. Fork this repository on GitHub, then clone it to your own computer.

2. Find a suitable quantitative dataset to analyze. This should be a primarily quantitative dataset. It would be best if you used a dataset that you cared about, but some suggested datasets include these:

- [Mapping Early American Elections](https://github.com/mapping-elections/elections-data), especially `congressional-candidate-totals.csv` or `congressional-counties-parties.csv`.
- County-level data from the 1906, 1916, 1926, or 1936 [Censuses of Religious Bodies](http://www.thearda.com/Archive/ChCounty.asp).
- Selected U.S. Census data of your choice from [NHGIS](https://www.nhgis.org).

3. Add your data to this repository as a CSV file. If it is more than one file, it should probably go in a `data/` directory.

4. Create an RMarkdown file in this directory in which you will do your analysis. Name it something sensible like `analysis.Rmd`. This file should read in your data using the `read_csv()` function in the readr package.

5. Using both prose and code, create an exploratory data analysis of your dataset. Use the techniques in Grolemund and Wickham as well as in Peng to figure out what the dataset is, what could be learned from it, and what potential pitfalls there are in the data. 

6. Edit your document to get rid of visualizations and prose that proved not to be useful.

7. Knit the document to HTML.

8. Submit a URL to your HTML document online as well as the URL to your GitHub repository.
