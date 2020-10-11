# Introduction
This file describes a top down approach to understanding charitable organizations in Canada, through the sociological lens of racialized immigrants, and people with disabilities and their interaction with environmental issues. Charities serving racialized immigrants and people with disabilities in Canada are identified from available Canada Revenue Agency data.

# Charities in Canada
Charities in Canada are incorporated organizations and are approved by Canada Revenue Agency (CRA) based on a set of criteria.
An important distinction in the social economy between Canada and other jurisdictions such as the US, is that non-profits in the U.S. are charities and can accept charitable donations unlike in Canada where not all non-profits are charities.
Charities in Canada are a specific legal organizational designation that can accept, for example, financial donations and issue charitable tax receipts.
Non-profits in Canada have a broader legal designation that cannot for example issue charitable tax receipts.
Detailed differences between charities and nonprofit organizations in Canada are described by [Canada Revenue Agency](https://www.canada.ca/en/revenue-agency/services/charities-giving/giving-charity-information-donors/about-registered-charities/what-difference-between-a-registered-charity-a-non-profit-organization.html).
Furthermore, nonprofits in Canada can be registered or incorporated at both federal and provincial levels.
Therefore, in Canada all charities are non-profits, but all non-profits are not charities.
This research focuses on charities in Canada, and specifically on data published by the CRA on Charities in Canada.

## Canada Revenue Agency
[Canada Revenue Agency](https://www.canada.ca/en/revenue-agency.html) is the regulator for the charitable sector in Canada.
The analysis also uses two sociological lenses, immigration and disability to analyze the data.
To this authors knowledge, no analysis of CRA T3010 data has been completed with a primary focus on racialized immigrants or people with disabilities. (reference Brouard and other research on T3010 Data)

### Canada Revenue Agency T3010 data
T3010 is the name of the CRA form through which charities in Canada file their primary financial reports with the government of Canada.
T3010 data is therefore the data filled out by Canadian charities in the CRA form.
T3010 data is vital not only to the government but also to researchers researching the social economy in Canada.
T3010 information is filed on an annual basis by charities, and therefore T3010 data provides the most current "snapshot" of charities in Canada.
It is useful to note that T3010 information is different from an "Annual Report" published by many Canadian charities.
Since T3010 data is information reported to the government in a standardized format, it is more amenable to analysis across hundreds or thousands of organizations.
Annual reports on the other hand, provide valuable information about the charity to constituents and stakeholders, but the non-standard formats make analysis beyond a limited number of reports impossible without substantial human resources.
Most usefully, T3010 data is provided by CRA to Canadian citizens free of charge.
* A public and searchable version of T3010 data per individual charity is provided on the [CRA website](https://apps.cra-arc.gc.ca/ebci/hacc/srch/pub/dsplyBscSrch?request_locale=en).  
* A less well known but still public file listing Canadian charities is provided through the Canadian Governments [Open Data Portal](https://open.canada.ca/en/open-data)
* A set of files providing the T3010 information completed by Canadian Charities is also provided to Canadian researchers through [informal information requests](https://www.canada.ca/en/revenue-agency/services/charities-giving/charities/information-about-a-charity.html)
The set of T3010 data files used for this analysis was obtained through an  informal information request, and was received in a CD by postal mail in July 2020.
An downloadable version was requested, but the CD by postal mail is the current process for distribution of these files.
The files requested and received cover 20 years of CRA T3010 data, and the files for the year 2018 are used here for initial analysis since it is the most recent and most complete set of CRA T3010 data.

### CRA T3010 data for 2018
The files for the year 2018 were used as they are the "most" complete.
Even though files for years 2019 and 2020 were available, they are not as complete as the 2018 file since there is a lag in reporting time.
i.e. data for 2019 is reported in 2020, and in July 2020 when the files were created, not all charities will have completed their reporting for 2019, including only ~ 200 organizations.
Similarly the file for 2019 only contains the reports for 2018 which have been submitted as of July 2020, a total of ~ 40,000 charities
2018 files containing information for ~ 85,000 charities therefore contain both recent and most complete set of CRA T3010 data.

The following files were provided for the year 2018:
1. Category_Sub-Category.csv
2. Country.csv
3. Designation.csv
4. Form Versioning Details.csv
5. Programs.csv
6. Province.csv
7. US State.csv
8. 2018-T3010-Basic Information-As of June 2020.csv
9. 2018-T3010-Donees-As of June 2020.csv
10. 2018-T3010-Financial Information-As of June 2020.csv
11. 2018-T3010-General Information-As of June 2020.csv
12. 2018-T3010-New and Ongoing Programs-As of June 2020.csv
13. 2018-T3010-Schedule 1-As of June 2020.csv
14. 2018-T3010-Schedule 2-As of June 2020.csv
15. 2018-T3010-Schedule 3-As of June 2020.csv
16. 2018-T3010-Schedule 5-As of June 2020.csv
17. 2018-T3010-Schedule 7-Description-As of June 2020.csv
18. 2018-T3010-Schedule 7-Outside Canada-As of June 2020.csv
19. 2018-T3010-Schedule 7-Resources-As of June 2020.csv
20. 2018-T3010-Trustees-As of June 2020.csv

#### Category_Sub-Category.csv File
This file contains the following fields:
* Category Code
* Category English Desc
* Category French Desc
* Sub-Category Code
* Sub-Category English Desc
* Sub-Category French Desc
* Charity Type
* English Desc
* Charity Type
* French Desc

The fields in the Category_Sub-Category.csv are designed to support two purposes, first to match the categories of charities laid out in legislaton: [Charities Registration (Security Information) Act](https://laws-lois.justice.gc.ca/eng/acts/C-27.55/index.html). Second codes rather than long form descriptions allow more efficient form data entry and verification.  

The Charity Type field in the Category_Sub-Category.csv file for example has four categories in accordance with the Charities Registration (Security Information) Act:

1. relief of poverty (food banks, soup kitchens, and low-cost housing units)
2. advancement of education (colleges, universities, and research institutes)
3. advancement of religion (places of worship and missionary organizations)
4. purposes beneficial to the community (animal shelters, libraries, and volunteer fire departments)

The short list of formal charity types is fairly restrictive, and the Category and Sub Category fields provide a more detailed set of classification possibilities.

 
