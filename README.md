
## Objective
The goal is to determine whether a customer will accept or reject a coupon.

## Dataset Description

The dataset consists of responses to the survey questions, with each row representing a unique scenario. The columns include:

- `scenario`: A description of the driving scenario presented to the participant.
- `destination`: The intended destination for the drive.
- `time`: The current time of day.
- `weather`: The weather conditions during the drive.
- `passenger`: Whether a passenger was present in the vehicle.
- `accept_coupon`: A binary indicator of whether the participant would accept the coupon if they were the driver.

There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

## Findings
- 56.8% of the drivers accepted the coupon for all the surveyed drivers totalling 12610
- During sunny weather, the driver whether male or female, has a higher probability of accepting a coupon v/s when its snowy or rainy. 
- Higher chances of accepting coupon if driver is alone
- Higher chances of accepting coupon if driver is going in the same direction as coupon destination
- Higher probability of accepting a Coffee house coupon or a restaurant < 20 coupon if destination is 'No Urgent Place' 
- Higher probability of accepting a coupon if
  a) destination is 'No Urgent Place' and with Friends for a Coffee house coupon 
  b) destination is 'No Urgent Place' and with Friends for a restaurant < 20 coupon
-Very low probability of accepting a coupon if occupation is 'Farming Fishing & Forestry" 
- 21 year old drivers have the highest coupon acceptance probablity
-  At 2PM carryout and take away coupons are rejected and restaurant (20-50) coupons are rejected at 10 AM. At 6PM, restaurant<20 is accepted

## Next Steps
- Combining additional columns "toCoupon_GEQ5min", "toCoupon_GEQ15min", "toCoupon_GEQ25min" to infer patterns
- Majority of the data in the dataset is categorical. One can create additional numeric columns to get frequency of coupons based on what the driver selected instead of 5 columns RestaurantLessThan20	Restaurant20To50,Bar , CoffeeHouse & CarryAway. Only 1 of this value can be saved



## Contact

For any questions or concerns, please contact [priyadarsheeni@gmal.com].

