# Environmental Grant Funding for Immigrant Groups in Ontario

This project investigates grant funding for immigrant groups in Ontario.
One hypothesis is that immigrant groups in Ontario are under represented in terms of number and value of grants for environmental projects.
We will examine the available evidence to support or reject this hypothesis.

## Ontario Trillium Foundation Grant Data

Ontario Trillium Foundation (OTF) is the largest grant foundation in Canada, and as a foundation entirely dependent on Ontario government funding, it is an instrument of government policy through granting priorities in the social economy.
One of the OTFs transparency initiatives has been publication of its grant administration information as Open Data Ontario Trillium Foundation Open Data.
The grant data published by OTF is useful for a number of reasons.
First, the grants include predefined categories of "population served", therefore we can determine the number and amount of grants based on population served.
Second, the grant data published by OTF includes grant streams, such as "Green people", which will enable identification of the number and amount of funds invested in each grant stream.
Third, contains some qualitative text description data on the the purpose of each grant, which can be examined for further insight.
There are three different datasets which provide the total set of grants by the OTF.
The OTF grant datasets provide a comprehensive view of funding through the foundation to social economy organizations serving equity deserving groups such as immigrant communities in Ontario.

## Limitations of OTF grant datasets
First, some grant datasets identify only one category of population served, therefore intersectional analysis is not possible for those grant datasets e.g. combining immigrants and women.
Second, some categories of population served include multiple groups e.g. the category Diverse Cultural Communities and Racialized Groups may include both newcomers and multi-generational immigrants.
Third, the grant streams can change over time, i.e. the grant stream Green People was not used before it was created, and there may have been a different stream for environmental grants.
Fourth, since the data is collected by OTF, it is essentially administrative information used by OTF manage grants, e.g. it does not for example include information on if the organization is immigrant led or is a mainstream organization applying for an immigrant focused grant.
Fifth, much of the data is essentially fields from grant applications input by grantees, and therefore includes uncorrected typographical errors.

The **original** Ontario Trillium Foundation (OTF) Grant Open Data files used for analysis were downloaded from this website:
[Ontario Trillium Foundation Open Data](https://otf.ca/open) September 6, 2020.
The downloaded file used for applying methodology and analysis can be found here: [otf_granting_data_since_april_1_2015_original2](https://github.com/ultush/ontario-trillium-foundation-grants/blob/master/otf_granting_data_since_april_1_2015_original2.csv)

This project uses a cleaned up version of the file, as there were a number of data typographical errors in the original file.
The cleanup process was completed using [OpenRefine](https://openrefine.org/)
The cleanup steps are found here for repeatability:  https://github.com/ultush/ontario-trillium-foundation-grants/blob/master/JSON-OpenRefine-cleaning-steps-OTF-since-2015.md
The cleaned up version of  the file can be found here: https://github.com/ultush/ontario-trillium-foundation-grants/blob/master/otf_granting_data_since_april_1_2015_original2-openrefine-output.csv
