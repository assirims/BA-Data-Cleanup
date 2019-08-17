## Project 2.1: Data Cleanup


## Step 1: Business and Data Understanding

_Provide an explanation of the key decisions that need to be made. (250 word limit)_

### Key Decisions:

_Answer these questions_

1. What decisions needs to be made?

A decision about the most appropriate location for a new store needs to be made.

1. What data is needed to inform those decisions?

Some of the data that is needed to inform our decision include:

- Sales from both existing stores of Pawdacity and also competitors.
- The size and number of competitive stores in selected area.
- Information about population&#39;s size, growth, and segmentations.
- The availability of facilities for pets in selected area.

## Step 2: Building the Training Set

_Build your training set given the data provided to you. Your column sums of your dataset should match the sums in the table below._

**After working on the data, I ended up with this training set which helped me to answer and match the next table.**

| **City** | **2010 Census Population** | **Total Pawdacity Sales** | **Households with Under 18** | **Land Area** | **Population Density** | **Total Families** |
| --- | --- | --- | --- | --- | --- | --- |
| **Buffalo** | **4585** | **185328** | **746** | **3115.5075** |
 ![](data:image/*;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAAlwSFlzAAAXEQAAFxEByibzPwAAAA1JREFUCB1jYGBgsAIAAD8AO+2bAfEAAAAASUVORK5CYII=)


_In addition provide the averages on your data set here to help reviewers check your work. You should round up to two decimal places, ex: 1.24_ **(see the attached excel file for more info)**

| **Column** | **Sum** | **Average** |
| --- | --- | --- |
| _Census Population_ | _213,862_ | **19442** |
| _Total Pawdacity Sales_ | _3,773,304_ | **343027.63** |
| _Households with Under 18_ | _34,064_ | **3096.72** |
| _Land Area_ | _33,071_ | **3006.48** |
| _Population Density_ | _63_ | **5.70** |
| _Total Families_ | _62,653_ | **5695.70** |

## Step 3: Dealing with Outliers

_Answer these questions_

Are there any cities that are outliers in the training set? Which outlier have you chosen to remove or impute? Because this dataset is a small data set (11 cities), **you should only remove or impute one outlier**. Please explain your reasoning.

Yes, there are two cities that are outliers in the training set; Cheyenne and Gillette. By conducting two different experiments, I would choose to remove the outlier data of the Gillette city. The essential reasons are that Cheyenne is not an outlier but rather a big urban city where high population density results in possible huge sales. In addition, Gillette is a true outlier as its demographic numbers are within the standard range, yet the sales of Pawdacity are high, and thereby, we could conclude that Gillette is an outlier.

