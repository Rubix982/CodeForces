# A. Hit the Lottery

**time limit per test**: 1 second
**memory limit per test**:256 megabytes
**input**: standard input
**output**: standard output

## Description

Allen has a LOT of money. He has n dollars in the bank. For security reasons, he wants to withdraw it in cash (we will not disclose the reasons here). The denominations for dollar bills are 1, 5, 10, 20, 100. What is the minimum number of bills Allen could receive after withdrawing his entire balance?

## Input

The first and only line of input contains a single integer n (1≤n≤109).

## Output

Output the minimum number of bills that Allen could receive.

## Examples

----------------------------

Input,

```text
125
```

Output,

```text
3
```

----------------------------

Input,

```text
43
```

Output,

```text
5
```

----------------------------

Input,

```text
1000000000
```

Output,

```text
10000000
```

## Note

In the first sample case, Allen can withdraw this with a 100 dollar bill, a 20 dollar bill, and a 5 dollar bill. There is no way for Allen to receive 125 dollars in one or two bills.

In the second sample case, Allen can withdraw two 20 dollar bills and three 1 dollar bills.

In the third sample case, Allen can withdraw 100000000 (ten million!) 100 dollar bills.
