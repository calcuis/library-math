# library Math

The `Math` library in the Solidity code above defines a set of mathematical functions that can be used in smart contracts. The functions include `max`, `min`, `average`, `ceilDiv`, `mulDiv`, `sqrt`, `log2`, and `log10`. The functions are all implemented as internal functions, which means that they can only be called from within the same contract or library.

The `max` and `min` functions return the greater or lesser of two provided `uint256` values, respectively. The `average` function returns the mathematical average of two `uint256` values, and the `ceilDiv` function performs division with ceiling rounding, which means that it always rounds up to the nearest integer.

The `mulDiv` function performs multiplication and division of `uint256` values, but includes additional logic to prevent integer overflow. It is implemented using assembly language for efficiency.

The `sqrt` function calculates the square root of a `uint256` value. It is also implemented using assembly language for efficiency, and includes additional logic to handle rounding. The function can perform both floor and ceiling rounding, depending on the `Rounding` parameter passed in.

The `log2` and `log10` functions calculate the base-2 and base-10 logarithms of a `uint256` value, respectively. They also include additional logic to handle rounding, and can perform both floor and ceiling rounding, depending on the `Rounding` parameter passed in.

Overall, the `Math` library provides a set of essential mathematical functions for smart contract development, with additional optimizations to prevent integer overflow and handle rounding.

### References

https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/utils/math/Math.sol
https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/utils/math/SignedMath.sol
