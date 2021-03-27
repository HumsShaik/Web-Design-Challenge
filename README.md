# Web-Design-Challenge - Web Visualization Dashboard (Latitude)

## Background

This Project utilizes HTML, CSS and Bootstrap along with Python (Jupyter Notebook using pandas, matplotlib and numpy libraries) to analyze Cities data to find relationship between cities latitude Vs. Temperature, Humidity, Cloudiness and Wind Speed using Scatter Plots. The scatter plot reveals correlation (positive, negative or no correlation ) in a large amount of data.

Individual pages for each plot have been created using jupyter notebook  along with the means by which we can navigate between them.

These pages contain the visualizations and their corresponding explanations. 

There is an index page (landing page), a comparison page where we can see a comparison of all of the plots, and Data page where we can view the data used to build the vizualizations.

The Data page is converted to .html file using a jupyter notebook and then this .html file is loaded into the Data page.

The dashboard can be viewed at: https://github.com/HumsShaik/Web-Design-Challenge.git

## Notes

This folder contains:

* A `Resources` folder that contains the `cities.csv` file.

* An `Images` folder that contains the four visualization plots from the analysis using Jupyter Notebook.

* A `Visualizations` folder that contains Seven HTML files that has entire dashboard content.

* A `styles.css` file that contains additional styling to the website, including image centering, navbar background color, media queries, color changes on hover, etc. in visualizations

* A Jupyter notebook called `Web-Design-Challenge.ipynb` that was used to read the CSV file into a dataframe and convert that into an HTML table to use in the website and also plots were created which are stored in images folder.

### Website Requirements

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.




