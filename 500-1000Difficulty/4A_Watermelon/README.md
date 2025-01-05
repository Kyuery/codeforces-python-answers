# Calculate the Area of the Watermelon Division

This Python program determines whether Pete and Billy can divide a watermelon into two parts, each weighing an even number of kilos, based on the weight of the watermelon they bought.

## Problem Description

Pete and Billy have purchased a watermelon with a weight of 'w' kilos. They both prefer even weights and want to divide the watermelon into two parts in a way that each part has an even weight. The two parts don't need to be equal, but they should be positive.

## Program Logic

The program follows a straightforward logic:

### Input

- Read the weight of the watermelon from the input.

```python
kilos = int(input())
```

### Check Conditions

- Check if the weight is even, greater than 0, and not equal to 2. If these conditions are met, they can divide the watermelon as desired.

```python
if kilos % 2 == 0 and kilos > 0 and kilos != 2:
    print("YES")
else:
    print("NO")
```

## Example

### Input

```
8
```

### Output

```
YES
```

In this example, Pete and Billy can divide the watermelon into two parts of 2 and 6 kilos, or two parts of 4 and 4 kilos.

This program efficiently solves the watermelon division problem as described in the problem statement.
