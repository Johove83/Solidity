# Joint Savings Account in Blockchain

## Results

This first image determines that there are two unique accounts associated to a common savings account.

![1](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/1accountaddresses.png)

The first transaction is demonstrated below where 1*10^18 wei (1 Ether) is transferred into the join account and verified in the balance.

![2](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/2trans1deposit1etheraswei.png)

The following image demonstrates the block's additive ability by receiving 10*10^18 wei (10 Ether equivalent) into the account for a total value of 11 Ether.

![3](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/3trans2deposit10etheraswei.png)

A final deposit of 5 Ether is received by the Joint Savings account and is verified to hold a total value of 16 Ether.

![4](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/4trans3deposit1etherasether.png)

The below depiction shows an equivalent of 5 Ether withdrawn from the joint account. Interacting with the contractBalance shows a balance of an 11 Ether equivalent. lastToWithdraw and lastWithDraw amount allow for account holders to view receipt of which account holder was responsible for any transaction and how much value that transaction held.

![5](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/5trans4withdraw5ethertoaccount1.png)

The final image further demonstrates that a withdraw of 10 Ether by the second account owner also reflects an overall reduction in joint account balance, in this case leaving a balance of 1 Ether. Interaction of the functions again offers transparency and accountability into a change in account funding.

![6](https://github.com/Johove83/Solidity/blob/main/Joint%20Savings%20Account/Execution_Results/6trans5weithdraw10ethtoaccount2.png)

## Summary

Blockchain, through Solidity and the Ethereum Virtual Machine, offers a simple-to-sue, low-cost, solution to the hassels of modern, physical banking systems. 

Simply, an address or addresses are attached to a common account. This account can be freely accessed by account owners at anytime. Able to immediately accept and/or withdraw funds at a moments notice. These transactions are transparent to the public in terms of a public image (address), last withdraw amount, and the balance of the contract; this without sacrificing anonymity to the account holders.