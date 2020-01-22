# Weather_Website

Data is more powerful when we share it with others who are curious! Thia website reviels a statitcal visualizations using HTML, and CSS to create a dashboard showing off the analysis. The data was taken from an online API source: located off of the API. It consists of different pages of of visualizations of data.

The API was in JSON format and I used Jupyter Notebook to organize the data in a dataframe. The data frame also helped me create a proper statistical visualization.

### Website

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting a `.csv` file as HTML. I used tools that sush as pandas. Pandas has a nifty method approprately called `to_html` that allows mer to generate a HTML table from a pandas dataframe. 

The website must consists a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries).

