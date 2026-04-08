# AgeValidator.sol
AgeValidator.sol8
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AgeValidator {
    uint public age;

    function setAge(uint _age) public {
        require(_age > 0, "Invalid age");
        age = _age;
    }
}
Implement basic smart contract features
Fix minor issue
Improve contract modularity
Add basic error message
