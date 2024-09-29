**Repository of Business Forcasting Assignment-3**

This repository contains assignment-3 of Busniess Forcasting about the time series data on which you want to practice creating Forecasting Models. 

Although, The periodicity of the data should be monthly or quarterly. 

Question2:- Detailed description of the data amd how to create a good data dictionary.

Answer:-

**Data Dictionary for Stack Overflow Questions Dataset**

This dataset contains monthly aggregated data of questions tagged with various programming languages and technologies on Stack Overflow. It tracks the number of questions related to different technologies over time, providing a snapshot of their popularity.

**Columns Description**

**Month**: The first day of each month representing the period of data collection.

Data Type: Date

Example Values: 2008-09-01, 2009-02-01

**C++**: Number of questions tagged with "C++" on Stack Overflow for that month.

Data Type: Integer

Example Values: 755, 848

**C#**: Number of questions tagged with "C#" on Stack Overflow for that month.

Data Type: Integer

Example Values: 1639, 2597

**TypeScript**: Number of questions tagged with "TypeScript" for the month (starts later).

Data Type: Integer

Example Values: 0, 500

**PHP**: Number of questions tagged with "PHP" for that month.

Data Type: Integer

Example Values: 474, 757

**Swift**: Number of questions tagged with "Swift" (begins later).

Data Type: Integer

Example Values: 0, 1

**Ruby**: Number of questions tagged with "Ruby".

Data Type: Integer

Example Values: 286, 286

**Go**: Number of questions tagged with "Go".

Data Type: Integer

Example Values: 0, 100

**SQL**: Number of questions tagged with "SQL".

Data Type: Integer

Example Values: 503, 668

**Kotlin**: Number of questions tagged with "Kotlin" (begins later).

Data Type: Integer

Example Values: 0, 600

**Shell**: Number of questions tagged with "Shell".

Data Type: Integer

Example Values: 65, 75

**C**: Number of questions tagged with "C".

Data Type: Integer

Example Values: 320, 331

**HTML**: Number of questions tagged with "HTML".

Data Type: Integer

Example Values: 328, 480

**Objective-C**: Number of questions tagged with "Objective-C".

Data Type: Integer

Example Values: 50, 209

**Perl**: Number of questions tagged with "Perl".

Data Type: Integer

Example Values: 130, 163

**Matlab**: Number of questions tagged with "Matlab".

Data Type: Integer

Example Values: 11, 27

**R**: Number of questions tagged with "R".

Data Type: Integer

Example Values: 6, 8

**Python**: Number of questions tagged with "Python".

Data Type: Integer

Example Values: 537, 630

**Java**: Number of questions tagged with "Java".

Data Type: Integer

Example Values: 634, 945

**Javascript**: Number of questions tagged with "Javascript".

Data Type: Integer

Example Values: 1129, 1202

**Notes**

TypeScript, Swift, and Kotlin have zero values in early months because they were introduced later or gained popularity after the dataset's initial start.

The Month column represents the first day of each month but aggregates the number of questions for the entire month.

**Usage**

The dataset is ideal for studying programming language popularity trends and can be used in time series analysis for forecasting future trends.

Question3:- Data Collection Methodology. State how the data is collected, by whom, how often, etc. 

Answer:-

**Data Collection Methodology:**

**Source:** The data appears to be collected from Stack Overflow, a popular Q&A platform for developers.

**Method:** It was likely obtained by web scraping or using the Stack Exchange Data Explorer or Stack Overflow's public API, which provides programmatic access to its database of questions and answers.

**Frequency:** The data is aggregated monthly, as indicated by the Month column, covering various programming languages and technologies.

**Collected By:** The specific collector or organization is unclear, but it could be compiled by developers, data scientists, or research teams interested in trends in programming languages over time.

Question4:- Why does this data set intrigue you?

Answer:-

This dataset is intriguing because it captures programming languages trends over time, reflecting how the popularity of different languages evolves. By forecasting future values, we can predict which languages will gain or lose prominence, helping developers and educators make informed decisions about what to learn or teach.

The dataset spans a long period, providing a rich base for temporal analysis and the application of various time series forecasting models like ARIMA, Exponential Smoothing, and LSTM networks.

It’s also fascinating from a technology perspective because it shows the rise and fall of programming languages and frameworks, helping us understand broader trends in software development and the industry’s shifting demands.
