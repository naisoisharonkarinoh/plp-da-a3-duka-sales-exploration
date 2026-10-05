# Duka Sales Exploration

## Project Summary

This project explores a simulated six-month sales dataset for Duka, a retail business operating across five branches in Kenya: Nairobi, Mombasa, Kisumu, Nakuru, and Eldoret.

The analysis uses Python, Pandas, NumPy, and Excel to investigate sales revenue, branch performance, product performance, weekday versus weekend sales, monthly trends, and selected online premium orders.

## Questions Answered

The analysis answers the following questions:

1. Which branch generates the highest and lowest revenue?
2. Which products sell the most by revenue and units?
3. How do weekend sales compare with weekday sales?
4. Which month has the highest and lowest revenue?
5. How much revenue comes from Premium products sold Online in Nairobi and Mombasa?

## Dataset

The dataset contains 1,000 simulated sales orders generated using a fixed random seed of 2026.

The data covers sales from January to June 2026.

Main columns include:

- `order_id`
- `order_date`
- `branch`
- `product`
- `quantity`
- `channel`
- `unit_price`

Derived columns include:

- `revenue`
- `month`
- `weekday`
- `is_weekend`
- `price_band`

## Tools Used

- Python
- Pandas
- NumPy
- Google Colab
- Microsoft Excel
- GitHub

## How to Regenerate the Data

Run the following command from the project folder:

```bash
python generate_data.py