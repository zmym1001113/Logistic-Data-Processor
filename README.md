# Logistic-Data-Processor
A tool design for my client, which reduce 90% of the time to fill out all the required data manually. 


# 📦 Delivery Cost Estimator

A small Python project that calculates estimated shipping weight and cost based on product quantity and box type.
It’s designed to automate part of a real-world logistics workflow — showing how even simple Python scripts can make operations more efficient.

## 🧠 What It Does

* Determines which **box type** (A, B, or D) to use based on quantity
* Calculates **total package weight** including cooling cubes and buffer materials
* Estimates **total product value** in USD
* Prints summarized results for different quantities

## 💻 Example Code

```python
result_30 = delivery_data(qty=30, usd_per_item=170)
print(result_30)

result_10 = delivery_data(qty=10, usd_per_item=170)
print(result_10)

result_50 = delivery_data(qty=50, usd_per_item=170)
print(result_50)
```

## 📊 Sample Output

```python
{'qty': 30, 'box_type': 'B', 'total_weight': 11809, 'total_usd': 5100, 'cooling_cubes': 6, 'net_weight': 10609}
```

## 🧩 Tech Stack

* **Language:** Python 3
* **Libraries:** None (pure Python)

## 🌍 Why I Built This

I wanted to solve a real-world business problem — quickly estimating shipment weight and cost for medical skincare exports.
Even without a tech background, this project helped me apply data logic to streamline repetitive work.
