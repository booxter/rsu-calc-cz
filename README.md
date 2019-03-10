Tiny calculator for tax burden set by Czech Republic on RSU grants that were
granted while being a tax resident of Czech Republic but vested when no longer
one.

The general idea behind the calculator is that one should pay taxes on the
proportion of each realized grant that corresponds to days that you were a tax
resident, of the total length of grant vesting.

The calculator considers exchange rate as set by Czech national bank for each
year. As well as it subtracts the regular 'tax payer' deduction to come up with
the final number.

Note that 'tax payer' deduction is the only deduction that applies for tax
non-residents. For example, if you were deducting the 'non working spouse' or
'child' tax credits before, they don't apply to tax non-residents.

The calculator calculates final value in CZK (Czech kronas). It also gives an
estimate in USD (for informational purposes only!).

If after deduction you still owe them money, be aware that when sending
international transfer to Czech tax authorities, that you send kronas and not
USD. Also, make sure that your bank doesn't substract wire transfer fees from
the amount sent, so that Czech "IRS" gets exactly what you owe them. Your bank
assistant should be able to help with it as long as you are explicit about the
requirement.

To use the calculator, just pass the tax year, and it will read from
`./grants<year>.csv` file. You can check an example `grants.csv` file included
with the calculator to figure out the intended input format.

```bash
$ ./rsu-calc-cz 2018
```
