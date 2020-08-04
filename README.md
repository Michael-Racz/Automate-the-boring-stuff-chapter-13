# Automate-the-boring-stuff-chapter-13

## readCensusExcel.py
This program will open the included file in this repo:"censuspopdata". This is an excel sheet containig census information from 2010. The program will then read and count the number of census tracts , and total population in each county, then writes the results to "census2010.py". It does this by extracting and counting the data, and puts it all in a dictionary. With the 'pprint' module imported, we use the pformat method on our newly formatted data to make a new python program. Once the code has been run once, there is no need to run readCensusExcel.py again. If any data is needed from the information in the Excel document, just call "import census2010" on the python program. 

## census2010.py
This is the output program from 'readCensusExcel.py'. It contains the data from the Excel sheet 'censuspopdata.xlsx' inside of a multi-tiered dictionary.

## censuspopdata.xlsx
This is the Excel sheet used in the 'readCensusExcel.py' and 'census2010.py' programs.
