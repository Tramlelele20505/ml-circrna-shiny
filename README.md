# ml-circrna-shiny
# AML circRNA Database

A Shiny web application for exploring and analyzing circRNA data from BeatAML and Lux-AML cohorts.

## Features

- **Download Page**: Download circRNA data from different cohorts and detection tools
- **Exploration Page**: Filter and explore circRNA data based on expression levels
- **Statistics Page**: Visualize circRNA distributions and expression patterns

## Data Cohorts

1. **BeatAML**: Contains only Acute Myeloid Leukemia (AML) cases
2. **Lux-AML**: Contains both AML and healthy samples

## Detection Tools

- circall
- ciri2
- findcirc2

## Installation

1. Install R (version 4.0.0 or higher)
2. Install required packages:
   ```R
   install.packages(c("shiny", "shinydashboard", "DT", "ggplot2", "dplyr", "tidyr", "plotly", "readr", "stringr"))
   ```

## Running the Application

1. Clone this repository
2. Open R and set the working directory to the project folder
3. Run the application:
   ```R
   shiny::runApp()
   ```

## Data Structure

The application expects the following directory structure:
```
.
├── Beat-AML/
│   ├── circall/
│   ├── ciri2/
│   └── findcirc2/
└── LUX-AML/
    ├── circall/
    ├── ciri2/
    └── findcirc2/
``` 
