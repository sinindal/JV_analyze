Solar-cell-data-analysis
========================

Solar cell data analysis using python modules pandas, matplotlib and pyqt

With this program you can perform analysis of production data of (silicon) solar cells. It provides a graphical user interface.

<b>Features</b>

- Unlimited number of large data sets (e.g. 100k cells takes a few seconds)
- Automatic data filtering, including the possibility of filtering data sets with different settings in one session
- Automatic rendering of an Excel report containing summary and yield loss information
- A selection of different graphs (the number of data sets is unlimited, but there are only 8 different colors)
- All the graphs are interactive: You can select the data sets to show, set the scale, axis labels etcetera
- Cross-platform - mainly tested on Windows; partially tested on linux; should also be compatible with Mac OS
- Multiple language support (work in progress)

<b>Install</b>

To install you can choose between two methods:
- download the source code and use it in combination with a python distribution installation (e.g. Python(x,y), Anaconda, Enthought on Windows)
- download the release file and run it direcly after unzipping (Windows only)

<b>Using the program</b>

Many of the features will be self-explanatory to solar cell engineers. On the left panel you can load data, in the middle you can filter data and on the right you can choose from various output commands. To help you get started there are three CSV data files that you can load and process with the program. The CSV files also show what format your data has to be in, in order for the program to process the data. When loading a data file the program recognizes the column names as they are in those CSV files (other columns will be ignored). Data entries in the relevant columns will only be accepted if they all contain a numerical value which is not negative.
