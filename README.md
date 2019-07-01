%% Pasadena real estate study of home prices based on zip code and square footage. 
%% Data pulled from zillow.com and is not 100% conclusive as this is sample representation only.


@relation ‘pasadenaRealEstate’

@attribute zip NUMERIC
@attribute price NUMERIC
@attribute bedrooms NUMERIC
@attribute baths NUMERIC
@attribute sf NUMERIC
@attribute type {House, Condo}

@data
91101,575000,3,2,864,House
91101,599000,1,1,792,House
91103,499000,2,1,780,House
91104,590000,2,1,610,House
91104,529000,2,1,740,House
91103,1395000,4,4,2373,House
91103,749000,3,2,1588,House
91103,599000,2,1,960,House
91104,869000,3,2,1414,House
91104,875000,2,2,1575,House
91103,575000,2,1,1006,House
91107,689000,4,2,1320,House
91106,4780000,5,5,5473,House
91106,879000,2,2,1584,House
91104,899000,3,2,1720,House
91107,928000,3,2,1545,House
91104,1595000,3,3,2078,House
91103,670000,3,3,1285,House
91103,620000,3,1,1056,House
91107,659000,2,2,900,House
91105,1799000,3,3,1852,House
91103,799000,3,3,1636,House
91103,639000,5,2,2480,House
91107,999000,4,3,2129,House
91104,1075000,3,3,1766,House
91103,840000,4,3,1477,House
91106,1099000,4,3,1530,House
