# Guide to P4 Consequence Assessment

## Table of Contents
1. [Introduction](1-introduction)
2. [How to fill spreadsheet](2-how-to-fill-spreadsheet)
	1. [Consequence Assessment](21-consequence-assessment)
	2. [Economy](22-economy)
	3. [Preconditions](23-preconditions)
	4. [Terminology](24-terminology)
3. [Description of assessment results](3-description-of-assessment-results)
4. [Description of economic consequences](4-description-of-economic-consequences)
5. [Deliverables](5-deliverables)
	1. [Spreadsheet](51-spreadsheet)
	2. [Report](52-report)

## 1. Introduction
This guide describes how the step P4 Consequence Assessment is applied.

The consequence assessment measures and compares the most suitable preservation formats from the step P2 Format Assessment and/or preservation levels, which alternatively can be in play, if none preservation formats were suitable.

## 2. How to fill spreadsheet
First and foremost, the deliverery of this step is a filling of the sheets “Consequence Assessment, “Economy” and “Preconditions” in the document ”Spreadsheet_Consequence Assessment”.

### 2.1. Consequence assessment
The sheet ”Consequence assessment” measures every preservation format/level candidate (currently: Existing preservation format, new preservation format and original format(s)) against an assortment of business areas and consequence types (time, money and quality) and one o the following values must be selected from a drop-down menu in the columns C, F and I :
* (-2) Significant negative consequence
* (-1) Limited negative consequence
* (0) No change
* (1) Limited positive consequence
* (2) Significant positive consequence

E.g. validation may prerequisite time demanding and manual workflows, which is why validation would then be scored (-2).

The consequences affect business areas, which can be selected from a drop-down menu in column A. If relevant, several business areas can be selected and the same business area can be selected several times depending on the type of consequence selected from a drop-down menu in column B. The consequences must then be described in the columns E, H and K. The business areas are as follows:
* Investment in machines and software
* Analysis and new legislation
* Conversion
* Transition to new conversion
* Validation
* Storage
* Dissemination

The consequence assessment table calculates a sum for every preservation format or level. The sum is used in the comparison and assessment of the suitability for every preservation format or level. The calculations derive from the columns D, G and J where the numeric values are automatically copied, so that an automatic sum can be given.

What is time, money and quality?
* Time is defined as the extent of manual and time demanding workflows
	* Money is defined as the consequences that may be converted to a monetary unit
	* Quality is defined as:
		* Better possibilities for automatic validation of data and 
		* Better preservation of significant properties.

OBS! You may freely add more columns if more preservation formats or levels are assessed, but then it will involve a customisation of the spreadsheet template i.e. among other securing that the automatic copying of numbers are correct. This will necessitate a firm understanding of how spreadsheets work.

### 2.2. Economy
The sheet ”Economy” contain economic figures for your selection of the business areas. Every area is filled with figures from the sheet “Preconditions”. Sum is given for ”continuous costs” and initial costs” for every preservation format or level. Subsums are calculated based on who bears the costs i.e. your archive or the data producers/their suppliers. The purpose of the sheet is to highlight where in the business areas the costs distribute, if they are associated with startup or operation and who bears the costs. With regards to the latter, it may as well be the data producers and their suppliers as it may be your archive, and the subsum shows hereby the total societal costs, irregardless of who bears them.

### 2.3. Preconditions
The sheet ”Preconditions” contain the figures, which are applied in the economic calculations in the sheet “Economy”. The figures must be adjusted according to needs. The figures include both basic numbers based off presumptions such as hourly prices for your archive and suppliers, price per terabyte, number of yearly submissions of the content type etc. The presumptions must as far as possible be up-to-date and reasoned, and for this reason they must be adjusted if necessary. Following the basic numbers are rows with adjustable values for every preservation format/level according to business area.

**Table 1.** The basic numbers used in ”Preconditions”. The prices must be adjusted if they are no longer valid. When you see an x, the number must be adjusted according to the content type!

|  | Number |  | Explanation of presumption  |
| --- |---| ---|---|
| Price per hour | 600 | EUR/hour | |
| Price per hour, consultant/developer | 1500 | EUR/hour | |
| Price per hour, dialogue with data producer | 2700 | EUR/hour | |
| Averafge price for storage | 1736 | EUR/TB/year |  |
| Average size of submissions | 1.3 | TB |  |
| Share of content type per submission | x | % |  |
| Yearly submissions | x | amount |  |
| Share of submissions with content type | x | % |  |
| Workhours for production of submission | x | hour |  |
| Error rate in conversion due to content type | x | % |  |

### 2.4. Terminology
The sheet ”Terminology” contain explanations of the spreadsheet terms and values of drop-down menus. The sheet is used for data validation and must therefore not be deleted. However, content may be adjusted when necessary. The sheet contains the following headings with related data validation values and explanations:
* Consequence types
* Business areas consequences
* Currency delimitation

## 3. Description of assessment results
The report must contain a description of the results of the “Consequence assessment” sheet. Here, every business area and related consequences must be described and reasoned for every preservation format/level and every type of consequence. Numbers from the sheet “Economy” and time estimations must be included.

E.g. 
*	2. Description of the consequence assessment results
	*	2.1. File format ODS
		*	2.1.1. Validation
			*	Money (numbers from the sheet ”Economy” must be presented)
			*	Time (time estimations must be presented)
			*	Quality
		*	2.1.2. Conversion

## 4. Description of economic consequences
Likewise, the report must contain a separate description of the economic consequences from the sheet “Economy”. The most crucial sums for respectively continuous costs and initial costs for both your archive and the data producers/their suppliers must be copied to two tables as shown below.

**Table 2.** Continuous costs associated with operation. Costs can be stated in total per year or per submission.

| Distribution |  | Figure |
| -------- |--------------| ----------|
| Your archive | EUR/year | *e.g.* 88,382 |
| Data producer/Their supplier | EUR/year | *e.g.* 115,042 |
| Sum | EUR/year | 203,424 |

**Table 3.** Initial costs associated with start-up.

| Distribution |  | Figure |
| -------- |--------------| ----------|
| Your archive | EUR | *e.g.* 218,299 |
| Data producer/Their supplier | EUR | *e.g.* 432,188 |
| Sum | EUR | 65,487 |

The calculations rely on several numbers that are preconditioned. The numbers must be adjusted for every new investigation and the adjustment are done in the sheet ”Preconditions”. From this sheet, the numbers are automatically transferred to the sheets “Consequence assessment” and “Economy”. The report must reason why the preconditioned figures have been selected.

## 5. Deliverables
The entire P4 Consequence Assessment is delivered as a spreadsheet and a report.

### 5.1. Spreadsheet
The document ”Spreadsheet_Consequence Asssesment” must be filled. It contains two analyses respectively a numerical assessment of consequences for time, money and quality and an economic assessment with calculations for continuous and initial costs connected to every preservation format/level assessed. 

### 5.2. Report
The spreadsheet must be accompanied by a report describing the execution of the assessment, the results and the conclusion. The disposition must at least include:
1. Introduction (must contain the main points of the conclusion)
2. Description of the results of the “Consequence assessment” sheet
3. Description of the economic consequences
4. Conclusion
