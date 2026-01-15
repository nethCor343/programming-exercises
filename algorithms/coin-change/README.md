# ATM Change Machine

This project implements an algorithm to simulate the cash dispensing logic of an automated teller machine (ATM). The goal is to solve the problem using a **Greedy Algorithm** approach to minimize the physical quantity of bills dispensed.

## Problem Description

The task is to program software for a simple ATM that holds an unlimited supply of bills in the following denominations:
**$50, $20, $10, $5, $1**.

Given a withdrawal amount `X`, the algorithm calculates the **minimum number of bills** needed to cover that amount.

### Inputs and Outputs

* **Input:** An integer `X` (where `X > 0`).
* **Output:** A detailed breakdown of how many bills of each denomination are dispensed.

## Algorithm Logic (Greedy Approach)

The algorithm follows a "greedy" strategy:

1.  Iterate through the available denominations sorted from highest to lowest (`[50, 20, 10, 5, 1]`).
2.  For each denomination, calculate how many bills fit into the current amount using integer division.
3.  Update the remaining amount using the modulo operator (remainder of the division).
4.  Repeat until the amount reaches 0.

---

## Examples

### Case 1: Standard Amount
**Input:** `126`

**Output:**
```text
$50 bills: 2
$20 bills: 1
$10 bills: 0
$5 bills:  1
$1 bills:  1
------------------
Total bills: 5