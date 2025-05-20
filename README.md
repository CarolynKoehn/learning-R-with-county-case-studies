# Learning R with county case studies
This is a series of research modules designed to both teach beginning R users how to work with data and lead undergraduates through research by constructing case studies of individual counties. These modules are designed to be completed asynchrounously. If students work on these independently, weekly debriefing sessions are helpful to work students through any difficulties they encounter. Students in a class with 40 required research hours typically completed between 3-4 modules and a presentation of their research.

# Contents
Each research module is contained in a separate folder containing a PDF of the instructions provided to students, an editable Quarto source file for the instructions, and instructor notes.

## Module 1: Getting Started in R

Objectives:
1. Download R and RStudio on your personal computer.
2. Create a single-value object, a vector, and a data frame.
3. Use number and character data.
4. Produce a Quarto report in PDF format to save a record of your work.

## Module 2: Navigating Data

Objectives
1. Read data into R.
2. Use commands that tell us information about a data frame.
3. Create subsets of data based on positions and conditions.
4. Use subsets to calculate metrics from two data sources.
5. Report on the average age of residents, average age of agricultural producers, population
size, percentage of residents in agricultural producer households, and percent of acres
used for agriculture in your case study county.

## Module 3: Agricultural Statistics, Part 1

Objectives:
1. Review percent calculations used in Module 2 to calculate statistics on producer gender
and race.
2. Use `unique` to calculate the variety of commodities produced by a county.
3. Use `ifelse` to assign categories and aggregate to calculate summary statistics for those
categories (farm size, farm ownership).

## Making Figures

At this point, students may need to make figures for a presentation of their research. The attached tutorial is not an in-depth module on data visualization, 
but merely a template for students who need to make figures with limited time.

Objectives:
1. Make comparison plots with ggplot.

## Module 4: Agricultural Statistics, Part 2

Objectives:
1. Use subsets, joins, and calculations across rows to quantify 20-year change in farm size
and ownership.
2. Use calculations based on a previous row (with `lag`) to quantify 20-year change in 5-year
intervals for agricultural land use and agricultural sales.
3. Use the `dplyr` package for data cleaning.

## Module 5: Demographic Data

Objectives:
1. Clean data by extracting column names from a multi-row header, filtering with `%in%`
statements, and matching variable codes to their meanings.
2. Increase reproducibility by using the `tidycensus package` to pull data from the online
American Community Survey data portal.
3. Calculate employment metrics (percent residents employed in agriculture, manufacturing,
hospitality, and technology), residents over retirement age, and net migration rate.

## Module 6: Reproducible Data Retrieval: Pulling Data Directly into R

Objectives:
1. Navigate the US Census API to locate variables of interest from the American Commu-
nity Survey.
2. Use the `tidycensus` package to pull data from the American Community Survey and
calculate a descriptive metric of interest.
3. Use the NASS Quick Stats page to locate variables of interest from the Census of Agri-
culture.
4. Use the `rnassqs` package to pull data from the Census of Agriculture and calculate a
descriptive metric of interest.

## Module 7: Working with Spatial Data

Objectives:
1. Use the `sf` package to explore and visualize vector data.
2. Use the `terra` package to explore and visualize raster data.
3. Use `sf` and `tigris` to retrieve a shapefile of a case study county.
4. Use a shapefile to crop a raster.
5. Calculate the frequency of each category in a categorical raster.

## Module 8: Spatial Data, Part 2

Objectives:
1. Use spatial summary statistics to calculate average agricultural quality.
2. Crop vector data and calculate land management percentages.
3. Use `freq` to calculate land cover percentages.

## Module 9: Migration Data

Objectives:
1. Calculate statistics for multiple counties at once using `summarise`.
2. Determine the difference in population size and density from source counties to study
area counties.
3. Join land cost data to migration data and calculate the difference in land value, using
`terra::extract`.
4. Determine the average household size of source counties.
