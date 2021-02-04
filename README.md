# Web-Design-Challenge
Web page [Weather/Latitude Analysis](https://krla20.github.io/Web-Design-Challenge/):
       
  [https://krla20.github.io/Web-Design-Challenge/](https://krla20.github.io/Web-Design-Challenge/)

## Latitude - Latitude Analysis Dashboard with Attitude
  * I used the cities.csv from my previous project and pictures from the [Python-API-Challenge](https://github.com/Krla20/python-api-challenge) not the data or pictures provided,     also, I changed the colors of my webpage from <sup>lightseagreen</sup> to <sup>purple</sup> .

### Website Requirements
* The website must consist of 7 pages total, including:

    * A landing page <sub>index</sub> containing:
      - An explanation of the project.
      - Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
      ![alt_text](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Latitude.PNG)
    - Four visualization pages, each with:
      - A descriptive title and heading tag.
      - The plot/visualization itself for the selected comparison.
      - A paragraph describing the plot and its significance.
      
      One sample visualization
      ![alt_text](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Temp.PNG)
      All visualization pictures can be found in [Latitude](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Latitude.PNG), [Temperature](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Temp.PNG), [Humidity](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Humidity.PNG) and [Wind Speed](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Wind_Speed.PNG)
      
    * A "Comparisons" page that:
      - Contains all of the visualizations on the same page so we can easily visually compare them.
      - Uses a Bootstrap grid for the visualizations.
      - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
      ![alt_text](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Comparison.PNG)
      
    * A "Data" page that:
      - Displays a responsive table containing the data used in the visualizations.
      - The table must be a bootstrap table component. Hint
      - The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe.
      ![alt_text](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/Data.PNG)

* The website must, at the top of every page, have a navigation menu that:

  1. Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  2. Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
  3. Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
  4. Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).
  
     [SmallScreen_dropdown](https://github.com/Krla20/Web-Design-Challenge/blob/main/Images/navigation_smallscreen.PNG)
