# Shark Attack
Project completed

# Project objective
Clean the dataset
Answer the question: "Where to sell anty-shark-spray and for whom"

# Methods

Filtering
Grouping


# Technologies

Python
Pandas

# Project Description
The shark attack dataset was at a bad state from the beginning, it had multiple points that needed cleaning before starting the analyses.\n
Empty columns, duplicated rows and bad data points where all infesting the data and the results.\n
After a broad cleaning the analysis could begin, so the first step where to discover the best countries to sell the product and to whom.\n

# Steps
The data set had structural and general problems but these one were not the most difficult to clean up.\n
the data points that were not in a regular pattern were the more time consuming.\n
A point that became clear to me is that there a some steps that you gonna need to generalize your problem but there are times that is easier to just attack a specific point.\n
A good example of this can be seen in the clean up of the age column where there where 2 main pattern breakers:\n

'str' - this first one were easier to solve case by case; ex: 'teen' - 13 

'30str' - these case were easier to use regex to find the number and substitute in all the rows;  ex: '30s' - 30

# Conclusion
USA and Australia represents 56% of global shark attacks and are leagues ahead of the third spot South Africa.\n
Of course coastal cities are the intended places to sell but from theses cities we have:\n

USA - Florida(29%), Hawaii(8%) e California(8%)

Australia - New south wales(13%), Queensland(8%) e Western Australia(5%)\n
After finding where to sell we have to find for who to sell.\n
Male dominate the shark attack victim with 80% of the cases\n
If we look to the age of the male group we can see that 75% of all attacks occur before the age of 35\n