# Test Design Techniques

Test Design Techniques are used to create effective test cases with minimum effort while ensuring maximum test coverage.

---

# Boundary Value Analysis (BVA)

## Definition

Boundary Value Analysis is a technique where test cases are designed using the minimum, maximum, and boundary values of the input range.

## Example

Age field accepts values from **18 to 60**.

Test Data:
- 17 ❌
- 18 ✅
- 19 ✅
- 59 ✅
- 60 ✅
- 61 ❌

---

# Equivalence Partitioning (EP)

## Definition

Equivalence Partitioning divides input data into valid and invalid groups (partitions). One value from each partition is selected for testing.

## Example

Age field accepts values from **18 to 60**.

Valid Partition:
- 18–60

Invalid Partitions:
- Less than 18
- Greater than 60

Sample Test Data:
- 15 ❌
- 25 ✅
- 65 ❌

---

# Decision Table Testing

## Definition

Decision Table Testing is used when the application's behavior depends on multiple conditions and their combinations.

## Example

| Username | Password | Expected Result |
|----------|----------|-----------------|
| Valid | Valid | Login Successful |
| Valid | Invalid | Login Failed |
| Invalid | Valid | Login Failed |
| Invalid | Invalid | Login Failed |

---

# State Transition Testing

## Definition

State Transition Testing verifies how the application behaves when moving from one state to another.

## Example

ATM Card

State 1 → Card Inserted

State 2 → PIN Entered

State 3 → Transaction Successful

If the user enters the wrong PIN three times, the card is blocked.

---

# Advantages

- Improves test coverage
- Reduces duplicate test cases
- Identifies edge cases effectively
- Saves testing time
