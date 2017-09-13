### Author: Pooja Reddy Yalala

### Project - Data Entry Analysis

### List of data files in this directory
##### 1. POOL2010.xlsx
##### 2. ZOOP-TEMP.xlsx
##### 3. ZOOP-TEMP-MAIN.xlsx
##### 4. DataEntryAnalysis.md
##### 5. Metadata.txt

### Background
Plankton are microscopic organisms that form the base of many aquatic food webs – fueling the growth of fish and other larger organisms. It’s common to sample them using a net or another container that can be controlled to collect water just from certain depths; so you can see how plankton collected at the surface (0 meters) might be different from plankton at another depth (e.g. 10 meters below the surface).

They are identified and counted under a microscope, and usually their numbers are reported as individuals per liter or milliliter.

Frequently, aquatic scientists collect plankton samples during both day (e.g. noon) and night (e.g. 2 am) because plankton change their distributions from day to night, and not all species alter their distributions in the same way.

The 3 files in this directory were all intended to be part of the same study – the investigators wanted to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies. The investigators plan to repeat this study for several more years.

### Tasks
##### Task 1: Problems in the way that the data are currently organized


1) Meta data is included in the datafile itself
2) There are few special characters in the column headers
3) No units mentioned for a few columns
4) Few cells are highlighted but the meaning is not explained anywhere
5) The timings of the data are not recorded
6) There might be duplication of the data
7) The data to be compared in recorded in different years making it difficult to compare and analyze
8) The names in the column headers are ambigious
9) There are few missing values and it cannot be deciphered if they are null values or the data is missing from the findings
10) There is a chart in Zoop-temp-main which is highly ambigious, as the labels for the X and Y axis are not given and the values in the X axis are overlapping making it difficult to be deciphered.
11) There are multiple files for the same data.

##### Task 2: Potential template for later years of data collection that would address these problems 

| Date | Time(EST) | Species | Colony Diameter(meters) | Density(kg/m^3) | Temperature(degree Celcius) | Depth(meters) | Chippos/Litre | Cunis/litre | Cuni Colony size(millimeter) | Cuni Colony size(millimeter) | Station | Chlrophyll A | Comments |
|------|-----------|---------|------------------------|-----------------|-----------------------------|---------------|---------------|------------|------------------------------|------------------------------|---------|--------------------|----------|
|      |           |         |                        |                 |                             |               |               |            |                              |                              |         |                    |          |
|      |           |         |                        |                 |                             |               |               |            |                              |                              |         |                    |          |
|      |           |         |                        |                 |                             |               |               |            |                              |                              |         |                    |          |
|      |           |         |                        |                 |                             |               |               |            |                              |                              |         |                    |          |
|      |           |         |                        |                 |                             |               |               |            |                              |                              |         |                    |          | 

1) There are no special characters in the column headers.
2) Units are mentioned for the columns whereever necessary.
3) Date along with time is included to help the scientists observe the changes in their distribution.
4) Names of the columns are clear and easy to understand.
5) All the data is collected in a single data file which makes it easy for the investigators to analyze and visualize the data.
6) All the meta data is included in a separate text file.
7) Additional column called Comments can be used to record additional findings/observations/comments.


