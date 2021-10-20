# Web Design Homework - Web Visualization Dashboard (Latitude)


## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

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

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits and a thorough README.md file

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

### Bonuses

* Use a different dataset! The requirements above still hold, but make it your own.
* Use a Bootstrap theme to customize your website. You may use a tool like [Bootswatch](https://bootswatch.com/). Make it look snazzy, give it some attitude. If using this, be sure you also meet all of the requirements listed above.
* Add extra visualizations! The more comparisons the better, right?
* Use meaningful glyphicons next to links in the header.
* Have visualization navigation on every visualizations page with an active state. See the screenshots below.

### Homework Web-Design Screenshots

#### <a id="landing-page"></a>Landing page

Large screen:

<img width="954" alt="landing lg" src="https://user-images.githubusercontent.com/87953612/138014559-aca1559d-ea6c-4f07-b2af-3e56e321b5f1.PNG">


Small screen:

<img width="293" alt="landing-sm" src="https://user-images.githubusercontent.com/87953612/138014604-0b15cc5c-bd1f-4633-ac05-b525d920787c.PNG">


#### <a id="comparisons-page"></a>Comparisons page

Large screen:

<img width="616" alt="comparisons-lg" src="https://user-images.githubusercontent.com/87953612/138014646-425249d3-c5e5-4689-970f-6269c7588dda.PNG">


Small screen:

<img width="295" alt="comparisons-sm" src="https://user-images.githubusercontent.com/87953612/138014666-b0d5e751-dc07-4756-affd-f9ea05de84ad.PNG">


#### <a id="data-page"></a>Data page

Large screen:

<img width="616" alt="data lg" src="https://user-images.githubusercontent.com/87953612/138014687-6132ed1e-d57e-4571-99ca-c378ad8c5c4a.PNG">


Small screen:

<img width="296" alt="data sm" src="https://user-images.githubusercontent.com/87953612/138014698-c580010e-5ce7-4f00-8e4e-f8cb77502ba4.PNG">


#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:

<img width="614" alt="visualization-lg" src="https://user-images.githubusercontent.com/87953612/138014717-bed3a06a-358b-4d41-b307-c4044e8c5501.PNG">


Small screen:

<img width="297" alt="visualization-sm" src="https://user-images.githubusercontent.com/87953612/138014727-a5c4e633-4007-4f35-9e9d-3f85f93a126c.PNG">


#### <a id="navigation-menu"></a>Navigation menu

Large screen:

<img width="619" alt="nav-bar-lg" src="https://user-images.githubusercontent.com/87953612/138014741-a286094b-8e06-454a-b489-34d85c2596b4.PNG">


Small screen:

<img width="308" alt="nav-bar-sm" src="https://user-images.githubusercontent.com/87953612/138014756-819d4885-6cd7-4c23-881c-c0bdf89fee34.PNG">

- - -

## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
