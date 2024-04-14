This repo analyzes the crimes in Chicago.

In "data" folder, dataset "Crimes_-_2001_to_Present.csv" should be downloaded from https://catalog.data.gov/dataset/crimes-2001-to-present and it includes comprehensive information about crimes in Chicago from 2001 to present.

Dataset "Police_Stations.csv" includes information of police stations in Chicago. 

Folder "Boundaries - Police Districts (current)" includes the geological boundary information of chicago, used for creating a scatterplot map of crimes.

Dataset "Zip_Codes.csv" includes the corresponding zip codes and location(latitude and longitude) of Chicago.

One should run "pre_data_for_draft.qmd" to generate a SQLite database called "Crimes_and_Police_Stations.sqlite" in "data" folder, and then run "Final_Project_Final_Draft.qmd" to generate any graphs and results.

One should run "pre_data_for_killer_plot.qmd" to generate a db database called "crimes_data_for_killer_plot.db" in "data" folder, and then run "presentation_final_version.qmd" to generate the presentation slides.

"killer_plot.qmd" includes only the killer plot code to be tested separately from other presentation code.
