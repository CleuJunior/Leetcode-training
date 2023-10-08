# Convert the Temperature

You are given a non-negative floating point number rounded to two decimal places _**celsius**_, that denotes the 
**temperature in Celsius**.

You should convert Celsius into **Kelvin** and **Fahrenheit** and return it as an array **_ans = [kelvin, fahrenheit]_**.

Return the array **_ans_**. Answers within **_10^-5_** of the actual answer will be accepted.

**Note that:**

- Kelvin = Celsius + 273.15
- Fahrenheit = Celsius * 1.80 + 32.00
 

**Example 1:**

- **Input**: celsius = 36.50
- **Output**: [309.65000,97.70000]
- **Explanation**: Temperature at 36.50 Celsius converted in Kelvin is 309.65 and converted in Fahrenheit is 97.70.

**Example 2**:

- **Input**: celsius = 122.11
- **Output**: [395.26000,251.79800]
- **Explanation**: Temperature at 122.11 Celsius converted in Kelvin is 395.26 and converted in Fahrenheit is 251.798.
 

**Constraints**:

- _0 <= celsius <= 1000_