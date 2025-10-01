# Supply Chain Questions

Different scenarios that might be encountered in the supply chain process.

* [Deciding between suppliers](#scenario-1)
* [Forecast demand and calculate the Safety Stock, ROP, and EOQ for 2 items]()

# Scenario 1

## Question

You have 3 suppliers for a critical manufacturing part with different lead times and prices. How do you treat Supplier A, Supplier B, and Supplier C?

| Supplier | Lead Time (Days) | Cost Per Unit | 
| -------- | ---------------- | ------------- |
| A | 14 | 3.50 |
| B | 21 | 2.75 |
| C | 28 | 2.00 |

## Answer

* Use Supplier C (low cost, high lead time) as the primary supplier and use them for as much demand as they can handle (cycle stock, safety stock, etc)
* Use Supplier A (high cost, low lead time) for urgent needs (stockouts, etc)
* Use Supplier B (medium cost, medium lead time) for situations when Supplier C and Supplier A cannot handle their respective roles

# Scenario 2

## Question

Given [historical monthly demand data](https://github.com/atamalu123/demand_planning/blob/main/original_data.csv) for two different items, forecast the demand using the most accurate strategy and calculate inventory metrics such as Safety Stock, ROP, and EOQ.

## Answer

The full Excel workbook and explanations can be found [here](https://github.com/atamalu123/demand_planning).
