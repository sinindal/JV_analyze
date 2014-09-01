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
- Supports multiple languages (English, Chinese and Dutch; Korean is a work in progress)

<b>Why not use a spreadsheet?</b>

The main advantage of using a dedicated program instead of a spreadsheet program like Microsoft Excel is that it performs much faster for large data sets (>10k cells). A low-to-high distribution plot for example takes less than a second, while the same plot using Excel takes a few minutes (on a i7-4800MQ/8 GB laptop using Excel standard function SMALL). Furthermore, the pandas and matplotlib libraries used for data processing and plotting are more powerful and flexible, so it is much easier to implement new features.

<b>Install</b>

To install you can choose between these methods:
- download the <a href="https://github.com/slierp/Solar-cell-data-analysis/archive/master.zip">source code</a> and use it in combination with a python distribution installation (e.g. Python(x,y), Anaconda, Enthought on Windows)
- go to <a href="https://github.com/slierp/Solar-cell-data-analysis/releases">releases</a>, download the zip file and manually run the exe file after unzipping
- go to <a href="https://github.com/slierp/Solar-cell-data-analysis/releases">releases</a>, download the setup file and install it (Windows only)

<b>Using the program</b>

Many of the features will be self-explanatory to solar cell engineers. On the left panel you can load data, in the middle you can filter data and on the right you can choose from various output commands. To help you get started there are three CSV data files that you can load and process with the program. The CSV files also show what format your data has to be in, in order for the program to process the data. When loading a data file the program recognizes the column names as they are in those CSV files (other columns will be ignored). Data entries for individual solar cells will only be accepted if all the relevant columns contain a numerical value which is not negative.

<b>Acknowledgements</b>

Polo Feng performed the translation in Chinese

Michael Rhieu performed the tranlation in Korean
