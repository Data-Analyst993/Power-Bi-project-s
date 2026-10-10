# Power-Bi-project-s
Moving Freight Profitably: A Data Story from
the Logistics Operations Database
By Omopenuola Favour Ayomide | TS Academy Data Analysis Capstone | Built with Power
BI and SQL
The Business at a Glance
A freight carrier lives or dies on three things: who it hauls for, what it hauls with, and who
drives. This analysis follows that chain through a logistics database of 14 linked tables,
using four dashboard pages: customers, delivery events, trucks and drivers. The company
serves 200 customers, runs 120 trucks across six brands and employs 150 drivers.
Executive Summary
Dedicated bookings anchor the revenue. They bring in 130M of 262.5M gross revenue,
about half, while refrigerated and dry van loads split almost evenly.
Customer value is spread across industries. Food/Beverage (109M) and Retail (104M)
lead on revenue potential, even though Automotive has the most customers (41).
Volvo and International trucks work hardest. They run about 860 trips per truck
against 600 to 670 for other brands, earn about 2.7M per truck against 1.9M to 2.1M, and
cost about 45K a year to maintain against 30K to 33K.
Maintenance is a small slice of revenue. At 4.33M against 257M, it is about 1.7%, and
between 1.5% and 1.7% for every brand.
Experience pays. Drivers in the 20 to 24 years band generate the most revenue (65M),
and Dallas is the strongest terminal (18.6M).
Chapter 1: Who We Serve
The customer base holds 200 accounts with a combined annual revenue potential of
537.65M.
By contract style: Contract customers are the largest group (75) and hold the largest
potential (206.8M, 38.5%). Spot follows with 63 customers (169.4M, 31.5%), then
Dedicated with 62 customers (161.5M, 30.0%).
Page 1 of 4
Moving Freight Profitably: A Data Story from the Logistics Operations Database
By industry: Automotive 41 customers, Food/Beverage 37, Retail 35, Electronics 33,
Consumer Goods 30, General 24.
By revenue potential: Food/Beverage 109M, Retail 104M, Automotive 97M, Consumer
Goods 87M, Electronics 75M, General 66M.
So what: Customer count and customer value do not line up. Retail and Food/Beverage
accounts are each worth about 3.0M, while Automotive and Electronics accounts are
worth about 2.3M to 2.4M. Automotive has the most accounts but ranks third on value, so
sales effort is best aimed at the higher-value industries.
Chapter 2: What We Earn
The delivery data records 171K events and 18.95M gallons of fuel. Gross revenue is
262.53M. Fuel surcharges add 29.98M (about 11% of gross), leaving operating revenue of
232.55M.
By booking type (gross / operating): Dedicated 130M / 115M, Spot 66M / 59M, Contract
66M / 58M.
By load type: Refrigerated 131.97M (50.27%) and Dry Van 130.56M (49.73%),
effectively a tie.
So what: Dedicated bookings generate roughly twice the revenue of Spot or Contract and
carry half of all surcharges (15M of 30M). Load type does not drive the business, so the
equipment mix is balanced, but the booking model clearly does. The customer page ranks
Contract customers first on potential, yet Dedicated bookings lead on realized revenue.
Customer type and booking type are different fields, but the gap is worth investigating.
Chapter 3: The Fleet
The fleet has 120 trucks with an average acquisition mileage of 26.06K and a fleet average
of 6.50 miles per gallon.
Peterbilt: 24 trucks, 45M revenue, 0.71M maintenance, 14.7K trips
Freightliner: 22 trucks, 42M revenue, 0.72M maintenance, 13.7K trips
Mack: 21 trucks, 39M revenue, 0.68M maintenance, 12.7K trips
Volvo: 20 trucks, 53M revenue, 0.90M maintenance, 17.2K trips
International: 18 trucks, 48M revenue, 0.83M maintenance, 15.5K trips
Kenworth: 15 trucks, 31M revenue, 0.48M maintenance, 10.0K trips
Page 2 of 4
Moving Freight Profitably: A Data Story from the Logistics Operations Database
So what: Brand totals mostly reflect fleet size, so the fair comparison is per truck. Volvo
and International look expensive to maintain, but they also run the most trips and earn the
most per truck. Their maintenance cost relative to revenue (about 1.7%) is no worse than
anyone else's. The real finding is utilization: Volvo and International are worked about 40%
harder than the rest of the fleet, which is where wear-related risk will show up first. Fuel
economy is 6.5 mpg on every brand, so brand does not explain efficiency.
Chapter 4: The People
The 150 drivers generated 257.26M in revenue.
By experience band: 0 to 4 years 35M, 5 to 9 years 44M, 10 to 14 years 54M, 15 to 19
years 50M, 20 to 24 years 65M, 25 years and above 10M.
By home terminal (top 10): Dallas 18.6M, Minneapolis 16.8M, Las Vegas 16.6M, New York
14.8M, Oklahoma City 14.5M, Seattle 12.7M, Los Angeles 12.7M, Columbus 12.5M,
Nashville 12.2M, Salt Lake City 10.8M. Dallas also burns the most fuel (1.3M gallons).
On-time delivery: even the best-ranked drivers sit between about 42% and 47%.
So what: Revenue climbs with experience up to the 20 to 24 year band, which makes
retention and mentoring a revenue question, not only an HR one. The 25 year band is
small, likely because few drivers are that senior, so totals there say little. Dallas leads, but
the top terminals are close, so growth does not depend on one location. The on-time rates
are low enough to deserve a closer look at how the measure is defined before drawing
conclusions about individual drivers.
Putting It Together
The story across the four pages is consistent: revenue is anchored in Dedicated bookings,
carried by a fleet whose Volvo and International units work hardest, and driven by
experienced people spread across a dozen terminals. The company's biggest question
mark is not cost, since maintenance stays near 1.7% of revenue, but service quality and
capturing the customer potential that is not yet turning into revenue.
Recommendations
1. Grow Dedicated bookings. Move more Spot and Contract customers toward
dedicated arrangements, since this model produces about twice the revenue per
booking type.
Page 3 of 4
Moving Freight Profitably: A Data Story from the Logistics Operations Database
2. Focus sales on high-value industries. Prioritize Retail and Food/Beverage accounts,
and review pricing for Automotive and Electronics, where each account is worth less.
3. Rebalance fleet use. Shift some trips from Volvo and International toward Peterbilt,
Freightliner and Mack, which run 600 to 670 trips per truck, and schedule preventive
maintenance for the high-use units.
4. Invest in driver retention. Pair drivers with 20 or more years of experience with newer
drivers through mentoring.
5. Audit on-time performance. Confirm the measure, set a target, and track it by driver
and terminal each month.
6. Close the potential gap. Compare each customer's revenue potential with what they
actually book, and start with the largest gaps.
Data Notes and Limitations
Revenue totals differ by page. The 537.65M figure is annual revenue potential from the
customer table. The 262.53M, 257.26M and 257.34M figures come from different tables
and filters, so confirm each page uses the same revenue source before final
submission.
Fuel gallons by truck brand (about 4K to 10K) do not reconcile with the 18.95M gallons
on the delivery page. Treat brand-level fuel figures with caution until the measure is
checked.
Average mpg is identical (6.5) across brands, which suggests the measure may not vary
by truck.
Per-truck figures and percentages were calculated from the chart values shown and
are rounded.
The dashboard does not yet cover route profitability, safety incidents or seasonal
patterns, which are the next logical extensions.
Method
The 14 source tables (customers, loads, trips, trucks, drivers, delivery events, fuel
purchases, maintenance records, safety incidents, routes, facilities, trailers and two
monthly metrics tables) were loaded into Power BI and related through their primary and
foreign keys. SQL was used for exploration and checks. Each page combines KPI cards,
slicers and charts to answer one business question.
