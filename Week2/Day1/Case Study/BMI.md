# ⚖️ C++ Program to Compute Body Mass Index (BMI)

## 🧩 Problem Statement

Write a C++ program that calculates a person’s **Body Mass Index (BMI)** based on their **weight** and **height**, and then classifies the BMI according to standard health categories.

Your program should:
1. Ask the user to enter their **weight (in kilograms)** and **height (in meters)**.  
2. Calculate the **BMI** using the formula:
    BMI = weight (in kilograms) / (height (in meters))²
3. Display the BMI value with **two decimal places**.
4. Classify the result as:
   - Underweight
   - Normal weight
   - Overweight
   - Obesity

---

## 🧠 Formula Explanation

The **Body Mass Index (BMI)** is a measure of body fat based on weight and height.

BMI = weight (in kilograms) / (height (in meters))²

### Classification Table:

| BMI Range | Category |
|------------|-----------|
| BMI < 18.5 | Underweight |
| 18.5 ≤ BMI < 25.0 | Normal weight |
| 25.0 ≤ BMI < 30.0 | Overweight |
| BMI ≥ 30.0 | Obesity |

---

## 💡 Example Inputs and Outputs

### Example 1:
**Input:**
Enter your weight (kg): 68
Enter your height (m): 1.75

**Output:**
Your BMI is: 22.20
Category: Normal weight

### Example 2:
**Input:**
Enter your weight (kg): 95
Enter your height (m): 1.70

**Output:**
Your BMI is: 32.87
Category: Obesity