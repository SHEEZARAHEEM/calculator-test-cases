# 🧪 Simple Calculator - Manual Test Cases

This document contains detailed manual test cases for a calculator that supports add, subtract, multiply, divide operations, including valid and invalid input scenarios.

---

## ✅ Valid Input Test Cases

### Test Case ID: TC_CALC_001
**Test Description:** Add two positive integers  
**Preconditions:** Calculator is open and functional  
**Test Steps:**
1. Enter `5`
2. Press `+`
3. Enter `3`
4. Press `=`
**Expected Result:** Displayed result is `8`

---

### Test Case ID: TC_CALC_002
**Test Description:** Subtract a negative number from a positive number  
**Preconditions:** Calculator is ready  
**Test Steps:**
1. Enter `7`
2. Press `-`
3. Enter `-4`
4. Press `=`
**Expected Result:** Displayed result is `11`

---

### Test Case ID: TC_CALC_003
**Test Description:** Multiply two decimal numbers  
**Preconditions:** Calculator is working  
**Test Steps:**
1. Enter `1.5`
2. Press `×`
3. Enter `2.0`
4. Press `=`
**Expected Result:** Displayed result is `3.0`

---

### Test Case ID: TC_CALC_004
**Test Description:** Divide a number by another  
**Preconditions:** Calculator is responsive  
**Test Steps:**
1. Enter `10`
2. Press `÷`
3. Enter `2`
4. Press `=`
**Expected Result:** Displayed result is `5`

---

### Test Case ID: TC_CALC_005
**Test Description:** Apply BODMAS (e.g., 2 + 3 × 4)  
**Preconditions:** Calculator supports operator precedence  
**Test Steps:**
1. Enter `2`
2. Press `+`
3. Enter `3`
4. Press `×`
5. Enter `4`
6. Press `=`
**Expected Result:** Displayed result is `14`

---

## ❌ Invalid Input Test Cases

### Test Case ID: TC_CALC_006
**Test Description:** Division by zero  
**Preconditions:** Calculator is running  
**Test Steps:**
1. Enter `9`
2. Press `÷`
3. Enter `0`
4. Press `=`
**Expected Result:** Error message or “Cannot divide by zero”

---

### Test Case ID: TC_CALC_007
**Test Description:** Input non-numeric characters  
**Preconditions:** Keyboard input allowed  
**Test Steps:**
1. Type `abc` into input  
**Expected Result:** Calculator should reject input or show error

---

### Test Case ID: TC_CALC_008
**Test Description:** Use multiple operators in a row  
**Preconditions:** Calculator is initialized  
**Test Steps:**
1. Enter `5`
2. Press `+` twice
3. Enter `2`
4. Press `=`
**Expected Result:** Calculator should ignore extra `+` or show error

---

### Test Case ID: TC_CALC_009
**Test Description:** Input special characters  
**Preconditions:** Calculator accepts typed input  
**Test Steps:**
1. Type `@#$%^`
**Expected Result:** Error or no action should occur

---

## 📌 Notes
- All tests are executed manually on [https://www.online-calculator.com/full-screen-calculator/](https://www.online-calculator.com/full-screen-calculator/)
- Results are noted as Pass/Fail during execution

---
