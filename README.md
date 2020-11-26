# California Alcohol Licenses

This package is a conversion of the California Daily ABC file, so it is current as of the modification date of the package. The main change is the addition of the ``county`` variable, the FIPS code for the county, and the ``tract``, the ACS format geoid version of the tract identifier. 

For the values for the ``license_type`` field, see https://www.abc.ca.gov/licensing/license-types/. The codes have general categories roughly noted by the tens digit, so you can divide by 10 to group them: 

* 0: Manufacturers and Distilleries
* 1: Importers, Borkers and Wholesalers
* 2: Off-sale (Sale for off-site consumption) and smalle wholesalers
* 4: On-sale
* 5: Clubs and caterers
* 6: On-Sale Seasonal sales,  B&B, Hospitals, Theater Companies, etc. 
* 7: Events, Farmers Markets
* 8: A Variety of odd types
* 9: Special Use

The most common types are: 

* 41; On-Sale Beer and Wine - Public
* 47: On-Sale General - Eating
* 21: Off-Sale General
* 20: Off-sale Beer and Wine
* 58: Catering
* 48: On-Sale General -- Public ( Bars and Nightclubs )