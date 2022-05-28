# NYC CONDOMINIUM ESTIMATED RENTAL INCOME
## Manhattan FY 2009 - 2010
#### Jonathan Jones 
#### 22.05.25
#### This project analyzes and compares condominiums in various Manhattan Neighborhoods.
#### Manhattan condominiums with similar sizes, and designs are compared against one another. Each unit’s location, market value, and attributes are analyzed to estimate its potential rental income. 

## DATA DICTIONARY
Column Name	Units	Column Description	Type
 Boro-Block-Lot	N/A	The Borough-Block-Lot location of the  condominium. The lot identifies the condominium billing lot generally associated with the condominium management organization.	Object
 Condominium	N/A	The  condominium is identified using a combination of a condominium number assigned by DoF followed by the condominium suffix. The condominium number is assigned by the Department of Finance for each condominium in New York City.  The condominium suffix is a partition of the condominium. A condominium may have multiple residential or commercial suffixes each of which contains individual condominium lots.	Object
 Address	N/A	The Street Address of the property	Object
 Neighborhood	N/A	Department of Finance determines the neighborhood name in the course of valuing properties. The common name of the neighborhood is generally the same as the name Finance designates. However, there may be slight differences in neighborhood boundary lines.	Object
 Building Class	N/A	The Building Class code  is used to describe a property’s use.  This report includes the two character code as well as the description of the building class.	Object
 Total Units	COUNT	Total number of units in the building	Numeric
 Year Built	YEAR	The year the building was built	Numeric
 Gross SqFt	SQFT	Gross square footage of the building	Numeric
 Estimated Gross Income	USD	Estimated Income per square foot * Gross square foot	Numeric
 Gross Income per SqFt	USD/SQFT	Estimated income per square foot of median comparable	Numeric
 Estimated Expense	USD/SQFT	Estimated Expense per square foot * Gross square foot	Numeric
 Expense per SqFt	USD/SQFT	Estimated expense per square foot of median comparable	Numeric
 Net Operating Income	USD	Estimated Gross Income-Estimated Expense	Numeric
 Full Market Value	USD	Current year’s total market value of the land and building	Numeric
 Market Value per SqFt	USD/SQFT	Full Market Value/ Gross square foot	Numeric
Comparable 1 Boro-Block-Lot	N/A	The Borough-Block-Lot location of the comparable rental property.	Object
Comparable 1 Address	N/A	The Street Address of the property	Object
Comparable 1 Neighborhood	N/A	Department of Finance determines the neighborhood name in the course of valuing properties. The common name of the neighborhood is generally the same as the name Finance designates. However, there may be slight differences in neighborhood boundary lines.	Object
Comparable 1 Building Class	N/A	The Building Class code  is used to describe a property’s use.  This report includes the two character code as well as the description of the building class.	Object
Comparable 1 Total Units	COUNT	Total number of units in the building	Numeric
Comparable 1 Year Built	YEAR	The year the building was built	Numeric
Comparable 1 Gross SqFt	SQFT	Gross square footage of the building	Numeric
Comparable 1 Estimated Gross Income	USD	Estimated Income per square foot * Gross square foot	Numeric
Comparable 1 Gross Income per SqFt	USD/SQFT	Estimated income per square foot	Numeric
Comparable 1 Estimated Expense	USD	Estimated Expense per square foot * Gross square foot	Numeric
Comparable 1 Expense per SqFt	USD/SQFT	Estimated expense per square foot	Numeric
Comparable 1 Net Operating Income	USD	Estimated Gross Income-Estimated Expense	Numeric
Comparable 1 Full Market Value	USD	Current year’s total market value of the land and building	Numeric
Comparable 1 Market Value per SqFt	USD/SQFT	Full Market Value/ Gross SqFt	Numeric
Comparable 1 Distance from Condo in miles	MILES	calculated distance from comparable to the 	Numeric
Comparable 2 Boro-Block-Lot	N/A	The Borough-Block-Lot location of the comparable rental property.	Object
Comparable 2 Address	N/A	The Street Address of the property	Object
Comparable 2 Neighborhood	N/A	Department of Finance determines the neighborhood name in the course of valuing properties. The common name of the neighborhood is generally the same as the name Finance designates. However, there may be slight differences in neighborhood boundary lines.	Object
Comparable 2 Building Class	N/A	The Building Class code  is used to describe a property’s use.  This report includes the two character code as well as the description of the building class.	Object
Comparable 2 Total Units	COUNT	Total number of units in the building	Numeric
