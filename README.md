# Airbnb Pricing & Market Analysis

Power BI report analysing Airbnb prices in 10 European cities and demand
seasonality (review volume) in 10 cities worldwide.
Group project (BI&B team of four), Nackademin Business Intelligence &
Analytics, BI26.

## Business questions
1. How do accommodation prices vary across European cities, and how does
   distance from the city centre affect price?
2. How do prices differ between weekdays and weekends?
3. How do room type and guest capacity affect price?
4. When is demand highest and lowest through the year (seasonality)?

## Report pages
**Pricing Analysis**
![Pricing Analysis](airbnb-pricing.png)

**Market Seasonality**
![Market Seasonality](airbnb-seasonality.png)

## Key findings
- Amsterdam has the highest average nightly price of the 10 cities.
- Centrally located properties cost more than those further out.
- Entire homes/apartments are the most expensive room type, and prices
  generally rise with guest capacity.
- Weekend prices are on average 2.79% higher than weekday prices; the
  premium varies by city (largest in Amsterdam).
- Review volume peaks in October (+28%) and is lowest in February (-32%).
- Paris and Rome have the most reviews overall.
- Northern and Southern Hemisphere cities have different seasonal peaks.
- A sharp drop in review activity is visible from March 2020 (COVID-19).

## Data model and DAX
Tables: Listings, Reviews, Weekends & Weekdays, plus a dedicated measures
table. DAX measures include average and median price per night, weekend
premium %, seasonality deviation % and total reviews.

## Tools
Power BI, DAX, Power Query, Deneb (custom visual)

## Data
[Name the dataset(s) and where they come from]

## My role
[One or two sentences on what you personally built]

## Team
Group project with three classmates at Nackademin.
