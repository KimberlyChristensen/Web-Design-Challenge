# Web-Design-Challenge

This project involves creating a webpage using data from the WeatherPy analysis.

## Website Specifications

The website consists of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A Comparisons page that:
  * Contains all of the visualizations on the same page to allow for easy visual comparisons.
  * Uses a Bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A Data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * Is a bootstrap table component. This incorporates the bootstrap responsive tables elements.    
	* Contains data derived from exporting the `.csv` file as HTML using pandas. 

In addition, the website has a navigation menu at the top of every page which:

* Has the name of the site on the left of the navigation bar which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive using media queries. 
