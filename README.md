# Data-Analysis
This is for Data analysis projects

********************************************************************************************
<p>Bertrand Ndakena, Telecom and IT Eng.</p>
<p>This is meant to help the user of this script run the code easily</p>
********************************************************************************************

                       **************************************
                       ******EXPLORING US BIKE SHARE DATA******
                       **************************************
                       
                       
## Introduction

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.
Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project,I used the data provided compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

## How to run the script
You can run the script using a Python integrated development environment (IDE) such as spyder. To install spyder, you will need to [download the Anaconda installer](https://www.anaconda.com/download/). This script is written in Python 3, so you will need the Python 3.x version of the installer. After downloading and installing Anaconda, you will find the spyder IDE by opening Anaconda Navigator. lauch the spyder, click on  open file and locate the script file.

## NOTE!!!:
1- place the csv data files in the same location as the script file (bikeshare.py)
2- make sure the csv files are  named, chicago.csv, new_york_city.csv and washington.csv, otherwise, the script won't run.

## Datasets
These datasets contain bike share data for the first six months of 2017. I randomly selected data for the first six months of 2017, provided for all three cities, Chicago, New York City and Washington.

The data is provided by [Motivate](https://www.motivateco.com/), which is a bike share system provider for many cities in the United States. The data files are to be placed in the same location as the this script file:

* Start Time
* End Time
* Trip Duration (in seconds)
* Start Station
* End Station
* User Type (Subscriber or Customer)

The Chicago and New York City files also contain the following two columns:
* Gender
* Birth Year

## Statistics Computed

I have clearly analyzed bike share data use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. Codes have been written in python to provide the following information:

*1* Popular times of travel ( occurs most often in the start time)

    most common month
    most common day of week
    most common hour of day

*2* Popular stations and trip

    most common start station
    most common end station
    most common trip from start to end (i.e., most frequent combination of start station and end station)

*3* Trip duration

    total travel time
    average travel time

*4* User info

    counts of each user type
    counts of each gender (only available for NYC and Chicago)
    earliest, most recent, most common year of birth (only available for NYC and Chicago)

## Perspectives
In the future, I intend to;
1. Upgrade this script so that it can display results in well formated table forms to ease facilitate reading by users
2. upgrade this script and cause it to generate and store each result in a separate csv file when executed
3. to create a stand alone application with this script, so that a user can run it with python installed on OS.

## References
Before I could realized this project, I referred to some websites and they were very helpful, they are listed below;
0. A general knowledge on the project with udacity python Introduction/ Data Analyst Nanodegree Program
1. The most frequent data from a data set
    https://www.geeksforgeeks.org/find-k-frequent-words-data-set-python/
    https://stackoverflow.com/questions/1518522/find-the-most-common-element-in-a-list
2. Assess datetime series:
     https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
     https://stackoverflow.com/questions/29366572/pandas-how-to-filter-most-frequent-datetime-objects

3. Filter date:
     https://stackoverflow.com/questions/29370057/select-dataframe-rows-between-two-dates

4. Check validity of date:
     https://stackoverflow.com/questions/9987818/in-python-how-to-check-if-a-date-is-valid/9987935

5. Add a day to a date:
     http://www.pressthered.com/adding_dates_and_times_in_python/

6. Read day of week, month, hour etc.:
     https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
     https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.dayofweek.html

7. Convert seconds to hours, minutes and seconds:
     https://stackoverflow.com/questions/775049/how-to-convert-seconds-to-hours-minutes-and-seconds
     https://docs.python.org/3/library/functions.html#divmod

8. Convert pandas series or dataframes to string:
     https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.to_string.html
     https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.to_string.html

9. Concatenate strings of two columns:
     https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python
     http://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.cat.html#pandas.Series.str.cat

10. Set column widths:
      https://pandas.pydata.org/pandas-docs/stable/options.html
      https://pandas.pydata.org/pandas-docs/stable/generated/pandas.set_option.html
11. Text color and background color
      http://ozzmaker.com/add-colour-to-text-in-python/

