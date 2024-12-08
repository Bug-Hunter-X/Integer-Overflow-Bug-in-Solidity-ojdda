# Integer Overflow Bug in Solidity

This repository demonstrates a common integer overflow bug in Solidity and its solution.

The `add` function in `bug.sol` does not handle cases where the sum of two unsigned integers exceeds the maximum representable value, leading to an incorrect result.  The `bugSolution.sol` file shows a safer implementation using SafeMath.