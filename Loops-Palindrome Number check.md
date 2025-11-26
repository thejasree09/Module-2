## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
num=int(input())
rev=0
temp=num
while temp>0:
    digit=temp%10
    rev=rev*10+digit
    temp//=10
if num==rev:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
## Output

<img width="987" height="256" alt="image" src="https://github.com/user-attachments/assets/9d1ce88e-5d68-4143-81b7-9986aa55f6a1" />

## Result
Thus,the program is executed successfully.
