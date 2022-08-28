# Performance Deferred Share

The Performance Deferred Share Program (PDSP) has been established by an organization to compensate eligible employees for their contribution to the long term performance of the organization. 

The final payout to the employee depends on the organization’s performance against its peer group. The PDSP valuation model is an attempt to value this liability taking this performance aspect into account.

For each award granted, 50% of the award consists of “regular” shares, while the
remaining 50% are “performance” adjusted. The payout on the performance shares is
adjusted based on how organization’s total shareholder return (TSR) compares to the peer group.

For the regular shares, the shares “vest” in three years from grant date, with dividends granted reinvested in shares. The final payout is based on the of the initial number of shares, included reinvested dividends.

As for the regular shares described above, in the Canadian program the increase or decrease will be applied to the number of shares at the end of the program including reinvested dividends. In the US program, since dividends are paid through the vesting period, only the original grant will be increased.

In order to value the payout of the performance deferred shares, one needs to model how the TSR will compare to the peer group at some future date. In order to do this, a correlated log-normal model was used to model the share price of each organization

Since we are modelling total shareholder return where the dividends are being reinvested, we can assume the drift for the TSR’s to be he risk free rate for each i. In fact, since the value will be eventually present valued using the same risk free rate, the risk free rate is not even required in the model. A long term historical average is taken for the volatility, as it is for the correlation. These appear to be reasonable assumptions to make.

As stated earlier, it will be necessary to compare the organization’s TSR against the peer group. For all three years of interest, one way to compare the performance of each bank would be to evaluate 

An alternate method of calculating this is based on a much more complicated “average” TSR over the whole period. The idea is to calculate the TSR for each share calendar quarter to quarter, and finally take an average return.

A performance deferred share may have an option to cancel out (see https://finpricing.com/lib/EqCallable.html)

