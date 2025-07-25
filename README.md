# # Sum of Digits – C Program

This simple C program takes an integer input from the user and calculates the **sum of its digits**.

## 🔢 Example

If the user inputs:
Enter the integer number: 5432

The output will be:

Sum of digits = 14

## 📁 File Structure

- `sum_of_digits.c`: Main C file containing the logic to compute the sum of digits.

## 🧠 How It Works

1. Take an integer input from the user.
2. Use a loop to extract each digit (`% 10`) and add it to `sum`.
3. Print the final sum.

## 🛠️ How to Compile and Run

### Using GCC:
```bash
gcc sum_of_digits.c -o sum_of_digits
./sum_of_digits
