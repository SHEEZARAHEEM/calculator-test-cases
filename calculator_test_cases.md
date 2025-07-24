# 🧪 Simple Calculator - Manual Test Cases

This document contains detailed manual test cases for a calculator that supports add, subtract, multiply, divide operations, including valid and invalid input scenarios.

1. ✅ Valid Input Test Cases

| Test Case ID   | Description               | Preconditions       | Test Steps          | Expected Result |
| -------------- | ------------------------- | ------------------- | ------------------- | --------------- |
| TC\_VALID\_001 | Add two positive integers | Calculator is ready | Enter `5 + 3 =`     | `8`             |
| TC\_VALID\_002 | Subtract two numbers      | Calculator is ready | Enter `10 - 4 =`    | `6`             |
| TC\_VALID\_003 | Multiply two numbers      | Calculator is ready | Enter `6 * 7 =`     | `42`            |
| TC\_VALID\_004 | Divide two numbers        | Calculator is ready | Enter `20 / 5 =`    | `4`             |
| TC\_VALID\_005 | Use decimal values        | Calculator is ready | Enter `5.5 + 2.3 =` | `7.8`           |


2. ➗ BODMAS Rule Test Cases

| Test Case ID   | Description                  | Preconditions       | Test Steps                                               | Expected Result |
|----------------|------------------------------|---------------------|-----------------------------------------------------------|-----------------|
| TC_BODMAS_001  | Multiply before Add (BODMAS) | Calculator is ready | Enter `5 + 3 * 2 =`                                       | 11              |
| TC_BODMAS_002  | Brackets handling            | Calculator is ready | Enter `(5 + 3) * 2 =` (if calculator supports brackets)   | 16              |
| TC_BODMAS_003  | Mixed operations             | Calculator is ready | Enter `10 - 2 + 3 * 4 =`                                  | 20              |


3. ❌ Invalid Input Test Cases

| Test Case ID     | Description               | Preconditions       | Test Steps             | Expected Result    |
| ---------------- | ------------------------- | ------------------- | ---------------------- | ------------------ |
| TC\_INVALID\_001 | Input alphabet characters | Calculator is ready | Try entering `A + B =` | Show error/invalid |
| TC\_INVALID\_002 | Special characters        | Calculator is ready | Enter `5 + $ =`        | Show error/invalid |
| TC\_INVALID\_003 | Division by zero          | Calculator is ready | Enter `5 / 0 =`        | Show error or `∞`  |


4. ⚠️ Edge Case Test Cases


| Test Case ID  | Description                 | Preconditions       | Test Steps                | Expected Result |
| ------------- | --------------------------- | ------------------- | ------------------------- | --------------- |
| TC\_EDGE\_001 | Large number multiplication | Calculator is ready | Enter `99999 * 99999 =`   | `9999800001`    |
| TC\_EDGE\_002 | Negative number addition    | Calculator is ready | Enter `-5 + -3 =`         | `-8`            |
| TC\_EDGE\_003 | Subtracting from zero       | Calculator is ready | Enter `0 - 10 =`          | `-10`           |
| TC\_EDGE\_004 | Small decimals              | Calculator is ready | Enter `0.0001 + 0.0002 =` | `0.0003`        |
| TC\_EDGE\_005 | Multiply with zero          | Calculator is ready | Enter `123456 * 0 =`      | `0`             |


✅ Status Overview

| Test Case ID         | Status                |
| -------------------- | --------------------- |
| TC\_VALID\_001–005   | ✅ Pass                |
| TC\_BODMAS\_001–003  | ✅ Pass                |
| TC\_INVALID\_001–003 | ❌ Error (as expected) |
| TC\_EDGE\_001–005    | ✅ Pass                |























## 📌 Notes
- All tests are executed manually on [https://www.online-calculator.com/full-screen-calculator/](https://www.online-calculator.com/full-screen-calculator/)
- Results are noted as Pass/Fail during execution


---
