# Project description
This vending machine is designed keeping in mind the following assumptions for simplicity:
1. Accepted denominations of money are Rs. 5 and Rs. 10
2. This machine sells only one item of cost Rs. 15

Working of machine:
If money is added in steps, then an item is sold after Rs. 15 and the machine goes back to reset state returning any excess money(money remaining after Rs. 15 is accepted)
If no money is added, then the money deposited in the previous steps is returned as a change.
