

#### Key Data Concepts:
+ Grainularity  (grain) (level of detail)  https://en.wikipedia.org/wiki/Granularity
+ primary key (unique identifier), different for each row ( can be a row number)
+ instances (rows)
+ attributes (columns)
+ filtering, slicing (selecting or removing rows from the data set)
+ ordering (changing the order of rows of the data set)
+ aggregation (summarizing data using a function such as sum or mean)
 
 #### Data Types
 + catagorical variable with a fixed number of possible values
	+ Zipcodes: 29412, 29413
	+ blood types A, AB+
	+ cities: Charleston, Summerville

 + numeric:
    * integer 1,2 ,2 3, examples are typically counts of things (number of cars a person owns)
    * continous (floating) 1.12321, 1.123312 

 + ID categorical variable where every element is unique, representing a primary key
    * Driver License Numbers, and social secuity numbers represent people)
    * transaction ids, may represent purshases
	
 + ordinal a catagorical variable where the categories are ordered, but where basic operations such as addition do not work
    * Months: Janurary, Feburary, ... 
    * Tempurature: cold, warm, hot

 + text: (tweets, reviews, ect ...)
 + Dates / Datetimes / Timestamps, tpyically represented as their own data type (in pandas, pyspark, databases and R data frames)
    * Often are accidently stored as string or categorical variables
    * build in functions can extract month, day, year, min, sec, as well as add and subtract time

 + images: typically stored as jpeg or similiar in directories that have a primary key in the directory name or in the image file name
 + videos
 + boolian (logical) True, False
 
 
 ### Basic Data Transformation
 + aggregation (summarize data by keys)
 + filtering (remove row or columns, by conditions )
 + pivoting (take one column, make each unique value it's own column.)
 + unvipoting (exploding/ melting, taking combining columns into rows)
 + joining (combine data sets by keys)
 

