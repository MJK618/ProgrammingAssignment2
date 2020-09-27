# Exploratory-Data-Analysis-Week-1-Project
Instructions

This assignment uses data from the UC Irvine Machine Learning Repository, a popular repository for machine learning datasets. In particular, we will be using the “Individual household electric power consumption Data Set” which I have made available on the course web site:

Dataset: Electric power consumption [20Mb]
Description: Measurements of electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.
The following descriptions of the 9 variables in the dataset are taken from the UCI web site:

Date: Date in format dd/mm/yyyy
Time: time in format hh:mm:ss
Global_active_power: household global minute-averaged active power (in kilowatt)
Global_reactive_power: household global minute-averaged reactive power (in kilowatt)
Voltage: minute-averaged voltage (in volt)
Global_intensity: household global minute-averaged current intensity (in ampere)
Sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
Sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
Sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.
Review criterialess 
Criteria

Was a valid GitHub URL containing a git repository submitted?
Does the GitHub repository contain at least one commit beyond the original fork?
Please examine the plot files in the GitHub repository. Do the plot files appear to be of the correct graphics file format?
Does each plot appear correct?
Does each set of R code appear to create the reference plot?
Reviewing the Assignments

Keep in mind this course is about exploratory graphs, understanding the data, and developing strategies. Here's a good quote from a swirl lesson about exploratory graphs: "They help us find patterns in data and understand its properties. They suggest modeling strategies and help to debug analyses. We DON'T use exploratory graphs to communicate results."

The rubrics should always be interpreted in that context.

As you do your evaluation, please keep an open mind and focus on the positive. The goal is not to deduct points over small deviations from the requirements or for legitimate differences in implementation styles, etc. Look for ways to give points when it's clear that the submitter has given a good faith effort to do the project, and when it's likely that they've succeeded. Most importantly, it's okay if a person did something differently from the way that you did it. The point is not to see if someone managed to match your way of doing things, but to see if someone objectively accomplished the task at hand.

To that end, keep the following things in mind:

DO

Review the source code.
Keep an open mind and focus on the positive.≤/li>
When in doubt, err on the side of giving too many points, rather than giving too few.
Ask yourself if a plot might answer a question for the person who created it.
Remember that not everyone has the same statistical background and knowledge.
DON'T:

Deduct just because you disagree with someone's statistical methods.
Deduct just because you disagree with someone's plotting methods.
Deduct based on aesthetics.
Loading the dataless 
When loading the dataset into R, please consider the following:

The dataset has 2,075,259 rows and 9 columns. First calculate a rough estimate of how much memory the dataset will require in memory before reading into R. Make sure your computer has enough memory (most modern computers should be fine).
We will only be using data from the dates 2007-02-01 and 2007-02-02. One alternative is to read the data from just those dates rather than reading in the entire dataset and subsetting to those dates.
You may find it useful to convert the Date and Time variables to Date/Time classes in R using the 𝚜𝚝𝚛𝚙𝚝𝚒𝚖𝚎()  and 𝚊𝚜.𝙳𝚊𝚝𝚎() functions.
Note that in this dataset missing values are coded as ?.
Making Plotsless 
Our overall goal here is simply to examine how household energy usage varies over a 2-day period in February, 2007. Your task is to reconstruct the following plots below, all of which were constructed using the base plotting system.

First you will need to fork and clone the following GitHub repository: https://github.com/rdpeng/ExData_Plotting1

For each plot you should

Construct the plot and save it to a PNG file with a width of 480 pixels and a height of 480 pixels.
Name each of the plot files as 𝚙𝚕𝚘𝚝𝟷.𝚙𝚗𝚐, 𝚙𝚕𝚘𝚝𝟸.𝚙𝚗𝚐, etc.
Create a separate R code file (𝚙𝚕𝚘𝚝𝟷.𝚁, 𝚙𝚕𝚘𝚝𝟸.𝚁, etc.) that constructs the corresponding plot, i.e. code in 𝚙𝚕𝚘𝚝𝟷.𝚁 constructs the 𝚙𝚕𝚘𝚝𝟷.𝚙𝚗𝚐 plot. Your code file should include code for reading the data so that the plot can be fully reproduced. You must also include the code that creates the PNG file.
Add the PNG file and R code file to the top-level folder of your git repository (no need for separate sub-folders)
When you are finished with the assignment, push your git repository to GitHub so that the GitHub version of your repository is up to date. There should be four PNG files and four R code files, a total of eight files in the top-level folder of the repo.

The four plots that you will need to construct are shown below.
