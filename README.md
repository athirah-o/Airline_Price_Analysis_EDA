## **Analysis on Airline Ticket Prices**
## **Content**

> A.  Introduction

> B.  What we would like to find from this analysis?

> C. Info on dataset

> D.  Data loading

> E.  Data cleaning

> F.  Summary of Data

> G.  Results and discussion: Analyzing data through visualization
1.  The most popular by categories:
    *   a) Airlines
    *   b) Source and destination city
    *   c) Departure and arrival time
2.  Price vs Categories:
    *   a) Airlines
    *   b) Class
    *   c) Source and destination city
    *   d) Departure and arrival time
    *   e) Days before departure
    
> H. Conclusion

# **A. Introduction**

The airline industry encompasses various businesses, called airlines, which offer air transport services for paying customers or business partners. These air transport services are provided for both human travelers and cargo, and are most commonly offered via jets, although some airlines also use helicopters.

Pricing of airline tickets is a complex process driven by algorithms, AI technology, historical data, and other strategies. The price will always on the move as it goes up and down frequently. This is because they used a process known as yield management to determing the ticket price with the aim to fill the airplane profitably. There are several factors that determining the ticket prices such as profiling of travelers,length of advance purchase, current sales volume, competition, peak dates, level of overbooking, and fuel prices.

In understanding how several factors affect the ticket price, we can have an advantage on how to get the best airfare deal for our travel.

# **B. What we would like to find from this analysis?**

1. Which airlines has the most booking?
2. Which city is the most popular as source and destination city among 6 metropolitan cities in India?
3. Is there any different in terms of number of booking based on departure and arrival timing?
4. Does price vary with Airlines
5. How much different between price of economy and business class?
6. Does price differ between source and arrival cities?
7. Do the timing of departure and arrival has effect on ticket price?
8. How days before departure affect the price?

# **C. Info of dataset**

This dataset is taken from kaggle and contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. Data was collected for 50 days, from February 11th to March 31st, 2022. There are 300261 datapoints and 11 features in the cleaned dataset.

### FEATURES

  1. Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

  2. Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

  3. Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

  4. Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

  5. Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

  6. Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

  7. Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

  8. Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

  9. Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

  10. Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

  11. Price: Target variable stores information of the ticket price.

# **H. Conclusion**

In conclusion, our analysis give a valuable insights of the aviation industry specifically on India domestic market. This analysis reveals pattern on how ticket price is affected based on various factor. There are different price point for full-serviced carrier such as Vistana and Air India with LCC such as IndiGO, GO_FIRST, AirAsia and SpiceJet. Full-service carrier is more expensive than LCC due to its premium offerings. Next, different class offer different point which business class is 2 to 5 times higher than economy class. Besides, price also varies according where is your origin and destination city. Some city offers more affordable price while other is more expansive. Furthermore, traveler should consider the timing of the departure and arrival as different timing gives different ticket price. Non-preferred timing usually is more cheaper and should be consider for traveler on a budget. Lastly, traveler should plan carefully when to travel as the nearer the days before departure, the more expansive ticket price. In general, by taking advantage of the ideal time to book and the most affordable flight options, travelers can save money by making better judgements and organising their journey.
