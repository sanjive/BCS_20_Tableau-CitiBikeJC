# BCS_20_Tableau-CitiBikeJC
BCS Tableau homework assignment on CitiBike JC 

Link to Tableau Public site: https://public.tableau.com/profile/sanjive.agarwal#!/vizhome/CitiBikeJCAnalytics/CitibikeStory

#Tableau data visualization assignment using CitiBike data.

For the assignment the CitiBike JC data was chosen. The data and the logo were downloaded from the Citibike web site for this analysis.
(https://www.citibikenyc.com/system-data) webpage.

The Assignment is to create a Storyboard that tells a visual story with supporting data that enagages a user to interact with the site and the data.


Steps peformed.

1. Downloaded the CitiBike Jersey City data for the year 2019 as 12 .zip files
2. ETL code developed using Python Jupyter notebook was used to:
  2a. systematically open the .zip archive
  2b. extract the .csv files (using a recursive method to find and etract the file)
  2c. the 12 files extracted were then merged into one signle .csv file
  2d. the columns of the file were modified to make them more readable
  2d. the merged file was then saved onto the local machine in preparation to be used in Tableau for analytics.
3. The data was then imported as text into Tableau
4. An intial filter was used to filter put records that had "Year of Birth" earlier than 1940.
  (There a number of records that resulted in the age of bike rider to be 130 yrs in some cases)
5. Next a few worksheets were created that would help with showing the CitiBike Jersey Map and plot the Bike Stations with the bike usage data
6. Some other worksheets were created to help answer eth CitiBike usage demographics.
7. These wrokshets were then grouped in to Workbooks to organize the visualization based on the 2 themes Bike and teh station and the Usage Demogrphics
8. These 2 workbooks were then used to create a StoryBook to allow a user to view this interactive story.

Below is the link to the short video of the Tableau CitiBike Jersey City.

