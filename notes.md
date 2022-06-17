# First assignment (Data quality/Monitor)

Roughly 12,000 accounts

Admin Boomi with Jesse - Google it!

Import into Power BI: Profile the Account Object - Profile accounts in Salesforce, for a given account, how many valid names, address, zip code, city, state, country, domain (Account with all fields) - How many? Profile the account object on its entirety

Denodo - Check information that they can load

## From Salim:

Jessica and Rafael will be working together as one unit on the following :
Data profiling - get access to the sales force account data and start to profile and measure the data quality for each of the columns

* 		Customer Name
* 		Customer Adress
* 		Customer City
* 		Customer State
* 		Customer Domain
* 		Customer Country

We need to measure by country the data completeness broken by account type such as enterprise versus medIum etc…

The results will be presented in a power BI data quality dashboard that can be shared with the rest of the organization. This exercise will serve as a pre-requisite for the Master Data Management tool. We have loaded the data to a SQL server and access can be obtained from Jesse or Sabina.

Moreover, Jesse will be training Jessica and Rafael on Boomi so he can transition some of the day to day operations and support

## Discussed with Jess:

Metrics to calculate:

- [ ] Number of duplicate records
- [ ] What % of the records are incomplete
- [ ] Number of invalid website domains
- [ ] Number of blank records in each column
- [ ] Number of records with foreign characters (i.e shipping_city)
- [ ] Validity of shipping_st vs. shipping_address_line_1
- [ ] Validate city, state/providence and country correlate
- [ ] Number of Opportunities per Account ID
