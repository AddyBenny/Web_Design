WEB
The Live Version is at https://addybenny.github.io/Web_Design/

Latitude - Latitude Analysis Dashboard with Attitude
Created a visualization dashboard website using visualizations i have created in the past (ref API). 
In building this dashboard, i created individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. Also i have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

The website consist of 7 pages total, including:
A landing page containing:
- An explanation of the project.
- Links to each visualizations page.

Four visualization pages, each with:
- A descriptive title and heading tag.
- The plot/visualization itself for the selected comparison.
- A paragraph describing the plot and its significance.

A "Comparisons" page that:
- Contains all of the visualizations on the same page so we can easily visually compare them.
- I used a bootstrap grid for the visualizations.
- The grid is a two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

A "Data" page that:
- Displays a table containing the data used in the visualizations.
- The table is a bootstrap table component.

Note: The data came from exporting the .csv file as HTML and converting it to HTML. I used Pandas method called "to_html" that allows you to generate a HTML table from a pandas dataframe.

The website has a navigation menu that at the top of every page:
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
- "Comparisons" which links to the comparisons page, and "Data" which links to the data page.

Tools used: HTML, CSS, Bootstrap

The Live Version is at https://addybenny.github.io/Web_Design/
