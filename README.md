# Project-1-
Matt, Patrick, and Joe Project 1
- See PDF presentation in repo for analysis + graphics

# The Scenario - High Energy Costs
You work at a large manufacturer based  in the United States. The CFO of the company has expressed frustration at how much commercial natural gas prices  are negatively impacting the firm’s bottom line. As a member of the firm’s corporate strategy office you have been tasked with identifying:
-  Alternative factory locations (at the State level) with a history of low energy prices
-  Key macro drivers of commercial natural gas prices

# Information Source - U.S Department of Energy 
After reviewing the available information sources the team decided to combine and analyze commercial and aggregate natural gas price data produced by the U.S. Department of Energy for the following reasons:
- Monthly data at the state and national level going back decades
- Differentiation between commercial and consumer markets
- Institutional Credibility
- Data covering relevant macro drivers (consumption, production, storage etc.)

# Information Source - Data Clean Up
Some of the issues the team encountered and overcame while cleaning the data included: 
- Spaces in headers when converting from a csv to datatable in pandas, complicating subsetting data;
- Different date reporting format, requiring date types to be harmonized prior to analysis 
- Poor data labeling, that needed to be clarified and corrected when analyzing and summarizing information

# Alt Location: States with lowest energy costs
The US states with the lowest and highest costs were determined by the team using data showing historical prices in $/Mcf since 1989:
- Alaska has experienced the lowest average commercial gas prices for the period shown.
- However, given the challenges operating would pose to our business, we propose performing a closer comparison of Nebraska and Utah, based on proximity to our customers and corporate offices. 

# Alt Location: Utah vs Nebraska Energy Cost Comparison
Provide additional data points for deciding 
between the downselected states, the team 
reviewed the descriptive statistics for Utah 
and Nebraska since 1989 :
- The mean price since 1989 is within 0.06 across both states 
- Most other summary statistics are similar, with Utah having exhibited lower price dispersion from the mean 
- The team recommends Utah as a potential state for a future factory given the stated preference of our CEO for energy prices to remain as stable as possible over time, in 
addition to low. 

# Macro Driver: Supply and Demand
As a commodity a key driver of natural gas prices domestically is supply and demand. Based on the data available, 
the team produced the following observations:
- Production has risen to high levels relative to demand over the last ~20 years
- This may have contributed to a negative price trend that has persisted since the mid-2000s

# Macro Driver: Seasonality of Gas Consumption
The team noticed substantial variability when reviewing total natural gas withdrawals since the mid 1970s in the United States. 
Upon further review, the team made the following observations:
- Despite substantial variation during short periods of time, the long term range remained consistent.
- The ebb and flow of withdrawals appears to coincide with the seasons when a 1-2 year time horizon is considered, with a steep incline observed during winter months. 

# Future areas of analysis
- Weather and Gas Prices Over Time 
- The global gas market (prices by location and macro economic drivers) 
- Price of alternative energy sources (renewables)
- An review of impact projections of future carbon taxation and/ or additional hydrocarbon regulation 
