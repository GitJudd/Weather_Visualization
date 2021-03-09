# Web Visualization Dashboard - Lite

## Background

Create a website to visually compare data from a CSV file. The CSV file has been provided by the end user.
The original CSV file (cities.csv) can be found in the Resoruces folder.


### Website Requirements

The website must consist of the following:

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
    * The table must be a bootstrap table component.
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. 

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Provides two more text links: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* A breakdown of the individual charts would be nice, but is not required.
* Is responsive.

### Considerations

* The images can be found: [assets folder](Resources/assets).
* Bootstrap is required.
* Deploy the website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Use a CSS media query for the navigation menu.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.
* Add extra visualizations! The more comparisons the better.
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state.

### Screenshots - Examples of expectations. 

This section contains screenshots from the end user as to the minimum expectations followed by a screenshot of the final product.

#### <a id="landing-page"></a>Landing page - Sample
![Landing page large screen](Images/landingResize.png){:class="img-responsive"}
#### <a id="landing-page"></a>Landing page - Final
![Landing page large screen](Images/landingFull_final.png){:class="img-responsive"}

#### <a id="comparisons-page"></a>Comparisons page
![comparison page large screen](Images/comparison-lg.png)

#### <a id="data-page"></a>Data page
![data page large screen](Images/data-lg.png)

#### <a id="visualization-pages"></a>Visualization pages
![visualize page large screen](Images/visualize-lg.png)

#### <a id="navigation-menu"></a>Navigation menu
![nav menu small screen](Images/nav-sm.png)