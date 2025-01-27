# Dashboard Iris

This Shiny application provides an interactive dashboard to visualize and analyze the Iris dataset.

## Features

- **Histograms**: Interactive histograms for Sepal and Petal dimensions based on species.
- **Scatter Plots**: Explore relationships between Sepal and Petal dimensions.
- **Boxplots**: Compare distributions of Sepal and Petal dimensions across species.
- **Density Plots**: View density distributions of selected variables.
- **Data Table**: An interactive table to explore the dataset.
- **Summary Statistics**: Key metrics like the number of observations and mean values for selected species.

## Installation

1. Install R and RStudio (if not already installed).
2. Install the required R packages:
   ```R
   install.packages(c("shiny", "shinydashboard", "ggplot2", "plotly", "DT"))
   ```


## Visualizations

- **Histograms**: Display distributions of Sepal Length, Sepal Width, Petal Length, and Petal Width for the selected species.
- **Scatter Plots**: Correlation between Petal Length vs Sepal Length and Petal Width vs Sepal Width.
- **Boxplots**: Compare variable distributions across species.
- **Density Plots**: Analyze the density of selected variables.

## Technologies Used

- **R**: Core programming language.
- **Shiny**: Framework for building web applications.
- **Shinydashboard**: Provides a dashboard layout.
- **ggplot2**: For data visualization.
- **Plotly**: For interactive plots.
- **DT**: For interactive data tables.


- The [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) used in this project.

