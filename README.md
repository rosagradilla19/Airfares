# Airline Fares Statistical Analysis

The purpose of this project is to analyze airline fares collected in the 90s when the airline industry was deregulated. The inspiration behind choosing this data was the curiosity of learning about airfares and what factors play a role in price determination. Since The Airline Deregulation Act in 1978, The United States federal law deregulated the airline industry, removing the federal government control over such areas as fares, routes, and market entry of new airlines. Therefore, it is now even more interesting to look into what drives pricing of certain trips. 

Description of variables:
S_CODE : starting airport’s code
S_CITY : starting city
E_CODE : ending airport’s code
E_CITY : ending city
COUPON : average number of coupons for that route (one-coupon flight is a non-stop flight, two-coupon flight is a one stop flight, etc.) 
NEW : number of new carriers entering that route between Q3-96 and Q2-97
VACATION: whether a vacation route or not
SW : whether Southwest Airlines serves that route or not
HI : Herfindel Index - measure of market concentration
S_INCOME: starting city’s average personal income
E_INCOME: ending city’s average personal income
S_POP : starting city’s population
E_POP : ending city’s population
SLOT : whether endpoint airport is slot controlled or not; this is a measure of airport congestion
GATE : whether endpoint airport has gate constraints or not; this is another measure of airport congestion
DISTANCE: distance between two endpoint airports in miles
PAX : number of passengers on that route during period of data collection
FARE : average fare on that route
