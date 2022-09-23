# Reentrancy-in-Solidity-Contracts

This repository contains two Solidity contracts; one is the victim contract, while the other is the attacker.

When you deploy the victim contract, deposit 7 ether into it. Copy its contract address and deploy the attacker to it; then click on its attack function.

Other things being equal, you should be able to reenter and have a total of 8 ether.

PS: These days, I will be pushing out more contracts to help you understand Solidity better.
