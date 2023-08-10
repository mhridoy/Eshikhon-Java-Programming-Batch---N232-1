# Assignment: The Mysterious Island's Light Puzzle

On a mysterious island, there's a puzzle that needs to be solved to open the entrance to a hidden treasure. The puzzle consists of a series of lights, each with its own switch. The island's legend says:

```"To find the treasure that's out of sight,
Turn on the lights, but not quite right.
Every third light should be off in the row,
Use the power of bits to make the entrance show."
```
### Your task is to write a program that simulates this puzzle:

There are N lights in a row, initially all turned off.
You can only use bitwise operations to solve the puzzle.
Every third light in the row should be turned off. All other lights should be turned on.
Input:

### An integer N representing the number of lights in the row (1 ≤ N ≤ 1000).

## Output:
A binary string of length N representing the state of each light. '1' means the light is on, and '0' means the light is off.

## Example:
For N = 10, the output should be 1101101101.

### Hint:
Consider using the bitwise AND operation to determine the state of each light.
