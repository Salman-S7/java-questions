# java-questions

Here are the questions in a cleaner **one-after-another format**, not in table form.

**4. Treasure Chest Attempts**

**Concepts:** Loop, if-else, break statement

A treasure chest has a fixed unlock code. Assume the correct unlock code is `4321`.

The user gets only **3 chances** to enter the correct code. If the user enters the correct code in any attempt, print:

```text
Chest Opened
```

If the user enters the wrong code in all 3 attempts, print:

```text
Chest Locked
```

Write a Java program using a loop and control statements.

**Example 1:**

```text
Input:
1111
2222
4321

Output:
Chest Opened
```

**Example 2:**

```text
Input:
1111
2222
3333

Output:
Chest Locked
```

---

**5. Magic Number Scanner**

**Concepts:** Function, loop, digit extraction, if-else

A number is called **magical** if its **first digit** and **last digit** are the same.

For example, `7897` is magical because the first digit is `7` and the last digit is also `7`.

But `1234` is not magical because the first digit is `1` and the last digit is `4`.

Write a Java function:

```java
isMagical(int n)
```

The function should return `true` if the number is magical, otherwise return `false`.

**Example:**

```text
Input:
7897

Output:
Magical Number
```

---

**6. Delivery Charge Calculator**

**Concepts:** Function, if-else, arithmetic

A delivery app charges a fixed delivery fee of ₹40 for orders within `5 km`.

If the distance is more than `5 km`, the app charges ₹10 extra for every additional kilometer.

For example, if the distance is `8 km`, then the first `5 km` cost ₹40. The extra distance is `3 km`, so the extra charge is `3 × 10 = ₹30`.

Total delivery charge = `40 + 30 = ₹70`.

Write a Java function:

```java
calculateDeliveryCharge(int distance)
```

The function should return the final delivery charge.

**Example:**

```text
Input:
8

Output:
70
```

---

**7. Digital Root Machine**

**Concepts:** Loop, nested logic, sum of digits

A machine takes a number and repeatedly adds its digits until only a single digit is left.

For example:

```text
9875 → 9 + 8 + 7 + 5 = 29
29 → 2 + 9 = 11
11 → 1 + 1 = 2
```

So the final answer is `2`.

Write a Java program to find the final single digit after repeatedly adding the digits.

**Example:**

```text
Input:
9875

Output:
2
```

---

**8. ATM Withdrawal Validator**

**Concepts:** Function, if-else, logical operators

An ATM allows withdrawal only when both conditions are satisfied:

The withdrawal amount must be a multiple of `100`.

The account balance must be greater than or equal to the withdrawal amount.

For example, if the balance is `5000` and the withdrawal amount is `1200`, withdrawal is possible because `1200` is a multiple of `100` and balance is sufficient.

But if the amount is `1250`, withdrawal is not possible because it is not a multiple of `100`.

Write a Java function:

```java
canWithdraw(int balance, int amount)
```

The function should return `true` if withdrawal is possible, otherwise return `false`.

**Example:**

```text
Input:
Balance = 5000
Amount = 1200

Output:
Withdrawal Successful
```

---

**9. Game XP Level Up**

**Concepts:** Loop, sum calculation, if-else

A player gains XP after completing missions in a game.

The program should first ask how many missions the player completed. Then it should take the XP earned in each mission.

After calculating the total XP, check whether the player can level up.

If total XP is `1000` or more, print:

```text
Level Up
```

Otherwise, print:

```text
Keep Playing
```

**Example:**

```text
Input:
4
200
300
250
300

Total XP = 1050

Output:
Level Up
```

---

**10. Lucky Dice Game**

**Concepts:** Loop, counting, if-else

A player rolls a dice `N` times.

The program should count how many times the player gets the number `6`.

If the player gets `6` at least `3` times, print:

```text
Bonus Unlocked
```

Otherwise, print:

```text
No Bonus
```

**Example:**

```text
Input:
6
1
6
3
6
6
2

Output:
Bonus Unlocked
```

Explanation: The number `6` appeared `3` times, so the bonus is unlocked.

---

**11. Elevator Overload Check**

**Concepts:** Loop, running sum, stopping condition

An elevator can carry a maximum weight of `500 kg`.

People enter the elevator one by one. The program should take each person’s weight as input and keep adding it to the total weight.

If adding a person’s weight makes the total weight more than `500 kg`, that person cannot enter safely.

Print how many people entered safely before the elevator became overloaded.

**Example:**

```text
Input:
100
120
80
150
90

Output:
4
```

Explanation: The first 4 people entered safely. Their total weight is `450 kg`. The next person’s weight is `90 kg`, which would make the total `540 kg`, so that person cannot enter.

---

**12. Exam Retake Eligibility**

**Concepts:** Function, if-else, counting failed subjects

A student gets marks in 3 subjects.

The result should be decided using these rules:

If all 3 subject marks are `40` or above, print:

```text
Pass
```

If only 1 subject mark is below `40`, print:

```text
Retake Allowed
```

If more than 1 subject mark is below `40`, print:

```text
Fail
```

Write a function to decide the result.

**Example 1:**

```text
Input:
55
72
41

Output:
Pass
```

**Example 2:**

```text
Input:
55
32
60

Output:
Retake Allowed
```

---

**13. Coin Saving Challenge**

**Concepts:** Loop, counter, running total

A student wants to save money to buy something.

The user enters the target amount and the amount saved every day.

Write a Java program to calculate how many days are needed to reach or cross the target amount.

For example, if the target is ₹1000 and the student saves ₹150 every day, then after 7 days the student will have ₹1050.

So the answer is `7`.

**Example:**

```text
Input:
Target = 1000
Daily Saving = 150

Output:
7
```

---

**14. Parking Fee Machine**

**Concepts:** Function, if-else, arithmetic

A parking system charges ₹30 for the first hour.

For every extra hour, it charges ₹20.

For example, if a vehicle is parked for `3` hours, the fee will be:

```text
First hour = 30
Extra 2 hours = 2 × 20 = 40
Total fee = 70
```

Write a Java function:

```java
calculateParkingFee(int hours)
```

The function should return the total parking fee.

**Example:**

```text
Input:
3

Output:
70
```

---

**15. Number Mood Detector**

**Concepts:** If-else, modulus operator, logical conditions

A number mood detector gives a mood to a number based on divisibility.

Use these rules:

If the number is divisible by both `3` and `5`, print:

```text
Super Number
```

If the number is divisible only by `3`, print:

```text
Happy
```

If the number is divisible only by `5`, print:

```text
Lucky
```

If the number is not divisible by `3` or `5`, print:

```text
Normal Number
```

**Example:**

```text
Input:
15

Output:
Super Number
```

---

**16. School Bell Timer**

**Concepts:** Division, arithmetic, control logic

A school bell rings every `45` minutes.

The user enters the total school duration in minutes.

Write a Java program to calculate how many times the bell rings during the school day.

For example, if the school duration is `180` minutes, then the bell rings:

```text
180 / 45 = 4 times
```

**Example:**

```text
Input:
180

Output:
4
```

---

**17. Vending Machine Balance**

**Concepts:** Loop, running sum, stopping condition

A vending machine item costs ₹35.

The user inserts coins one by one. The machine should keep accepting coins until the total inserted amount becomes at least ₹35.

After that, print:

```text
Item Purchased
```

Also print how much extra change should be returned.

For example, if the user inserts ₹10, ₹10, ₹10, and ₹10, the total is ₹40. The item costs ₹35, so the change is ₹5.

**Example:**

```text
Input:
10
10
10
10

Output:
Item Purchased
Change: 5
```

---

**18. Alien Signal Strength**

**Concepts:** Loop, digit extraction, counting, if-else

A space station receives a signal number from an alien planet.

To check the signal strength, the system counts how many even digits and odd digits are present in the signal number.

If the number has more even digits, print:

```text
Stable Signal
```

If the number has more odd digits, print:

```text
Unstable Signal
```

If both counts are equal, print:

```text
Balanced Signal
```

For example, in `24851`, the even digits are `2`, `4`, and `8`, so even count is `3`. The odd digits are `5` and `1`, so odd count is `2`.

Since even digits are more, the signal is stable.

**Example:**

```text
Input:
24851

Output:
Stable Signal
```

