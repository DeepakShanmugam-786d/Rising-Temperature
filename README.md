# 🌡️ Rising Temperature

## 📌 Problem Description

We have a table called **Weather** that keeps track of the temperature for each day. The table looks like this:

| id | recordDate | temperature |
|----|------------|-------------|
| 1  | 2015-01-01 | 10          |
| 2  | 2015-01-02 | 25          |
| 3  | 2015-01-03 | 20          |
| 4  | 2015-01-04 | 30          |

### 📊 What do the columns mean?
- **id**: A unique number for each day.
- **recordDate**: The date when the temperature was recorded.
- **temperature**: The recorded temperature on that date.

---

## 🎯 Goal: Find Dates When the Temperature Increased
We need to find **all dates where the temperature was higher than the previous day (yesterday)**.

### ✅ Expected Output
Our output should look like this:

| id |
|----|
| 2  |
| 4  |

### 🔍 Explanation:
- **January 2, 2015 (id = 2)**: The temperature increased from **10** to **25** ✅
- **January 3, 2015 (id = 3)**: The temperature dropped from **25** to **20** ❌
- **January 4, 2015 (id = 4)**: The temperature increased from **20** to **30** ✅

So, the **correct answer is id = 2 and id = 4**.

---

## 🔥 How to Solve
Here’s the game plan:

1️⃣ **Compare each day’s temperature to the previous day’s temperature.**  
2️⃣ **If today's temperature is higher, select the id.**  
3️⃣ **Return the results in any order.**

---

## 🏆 Why is this important?
This type of data analysis is useful for:
- **Weather prediction** 📈
- **Climate change studies** 🌍
- **Energy usage forecasting** ⚡

🚀 Now you’re ready to write a query and find the rising temperatures!

