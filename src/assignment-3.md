# Assignment 2

Ishan Pranav, Yerim Ryoo, and Pavan Chand

April 3, 2025

Professor Arpit Gupta

FINC 2339 Real Estate Capital Markets

## Short Question 1: Agency MBS valuations

This section discusses data on agency mortgage-backed securities (MBS).

### Short Question 1 Part A

> What is the difference between the columns “Bond” and “WAC?” Why is WAC higher
> than Bond? What does the difference between the two represent?

Based on the MBS prices and spreads for July, the "Bond" and "WAC" columns refer
to two different types of coupon rates.

The "Bond" column refers to the standard bond rate, or the coupon rate of the
MBS pool paid to the MBS investors.

The "WAC" or Weighted Average Coupon column refers to the average coupon rate
paid by the borrowers of the underlying mortgages in the pool, weighted by the
underlying loan balances.

In general, the WAC rate is higher than the Bond rate because not all of the
income generated from the underlying loan pool is paid out to investors.
Servicing and guarantee fees, as well as any excess costs, account for the
spread between the WAC rate and the Bond rate. Also, bond rates must be aligned
to fixed intervals, such as 50 bps, whereas the weighted average coupon is a
precise figure.

### Short Question 1 Part B

> Average loan size is lower for higher coupons. Why do you think that is?

The average loan size tends to be lower for higher coupons because homeowners
are rate-sensitive and are averse to higher coupons. Holding borrowers' budgets
fixed, during periods of high interest rates they must take lower loan balances
to keep their monthly payments affordable.

### Short Question 1 Part C

> Is the reported yield (or the yield spread to Treasuries) a good measure to
> decide which of these MBS coupons you may want to invest in? What are its
> shortcomings?

The yield and yield spread are useful measures for MBS investors; however, they
have shortcomings.

Unlike the Z-spread, the static yield spread does not account for changes in the
interest rate. The static yield spread uses a single value for the Treasury
yield, whereas the Z-spread uses the entire yield curve to determine the
constant spread earned above each cash flow's individual Treasury rate.

Unlike the option-adjusted spread (OAS), the yield spread does not account for
the prepayment risks across rate environments.

Since these mortgages are agency-backed, investors do not need to fear loss of
principal; however, when a borrower defaults, the agency prepays the mortgage.
So, credit risk still contributes to prepayment risk.

Thus, while an MBS pool with a high yield spread to Treasuries may seem
attractive, it is important to consider the interest-rate, credit, and
prepayment risks that may explain and offset the higher yield.

### Short Question 1 Part D

> What is the interpretation of OAS? Based on the OAS values, which coupons
> would be the best investment? Are there any caveats to this?

The option-adjusted spread (OAS) is the spread over the Treasury yield curve
that makes a mortgage bond's present value equal to its market price, after
accounting for prepayment risk. In other words, it is a Z-spread, adjusting for
the value of the borrower's option to prepay. 

The OAS accounts for the yield curve as well as prepayment risk, and is thus
lower than the static yield spread and Z-spread.

In general, investors should prefer the bonds with the highest option-adjusted
spreads, such as the 6.5-percent and 6.0-percent coupon bonds (assuming that we
may only pick two), which have Treasury option-adjusted spreads of 102 bps and
96 bps, respectively (or OAS of 84 bps and 78 bps, respectively).

One caveat is that the calculation of the option-adjusted spread is imperfect
and depends on the quality of the model used. The option-adjusted spread is
computed using a stochastic simulation, rather than a deterministic formula.
This means that a bad model may under- or overestimate the prepayment risk.

### Short Question 1 Part E

> What is the interpretation of the option cost? Why do you think the 2.5 coupon
> has a low option cost?

The option cost is the difference between the Z-spread and the OAS; in other
words, it is the value of the borrower's embedded prepayment option, or the cost
of that option to the lender.

The Z-spread overestimates investors' returns because it does not estimate and
subtract away the losses that investors may face if borrowers exercise their
option to prepay when the bond trades at a premium (in low-rate environments).

The 2.5-percent coupon bond has a low option cost because low-coupon bonds are
less sensitive to prepayment risk.

* If borrowers already have a mortgage at a low rate, the interest rate must
  fall *significantly* to make refinancing (prepayment) worthwhile.
* Borrowers in the 2.5-percent mortgage pool have weighted average coupons of
  3.10 percent. Since it is unlikely that rates will fall below 3.10 percent, it
  is also unlikely that borrowers in this pool will refinance.
* Even if rates fall below 3.10 percent, the new market rate will likely not be
  low enough to make prepayment attractive.
* The low coupon rate encourages borrowers to keep their "locked-in" mortgage.

As a result, the prepayment option is worth very little to the borrower and thus
costs the lender very little.

### Short Question 1 Part F

> Which of the coupons has the most interest rate risk (and what statistic do
> you look at to determine this)?

Interest-rate risk refers to the potential loss of value from a fluction in
interest rates. If interest rates rise, then the present value of an investment
decreases due to discounting.

Interest-rate risk disproportionately affects longer-duration investments since
the discount factors are compounded over more periods.

The average life (AL) of a loan can be used as a proxy for its duration. Since
the 2.5-percent bond has the greatest average life, we expect it to be the most
sensitive to increases in the interest rate. When the interest rate rises above
2.5 percent, we expect this bond to trade at a discount. If we use OAS DUR,
another measure of duration, we arrive at the same conclusion.

### Short Question 2 Part G

> Which coupon has the highest projected prepayment speed? Why do you think it
> has higher prepayment speeds than the lower and higher coupons?

Based on the data, the 6.0-percent coupon bond has the highest projected
prepayment speed, with a long-term conditional prepayment rate (CPR) projection
of 32. In the short term, the 5.5-percent coupon bond has a higher CPR
projection of 40.

In general, we expect higher coupon bonds to have higher prepayment speeds,
since it is more likely for the market interest rate to fall below the coupon
rate, giving borrowers the opportunity to refinance to a lower rate.

Since both the 5.5- and 6.0-percent coupons have high weighted-average coupon
rates (6.11 percent and 6.63 percent, respectively), and both are above 6
percent, we expect these to have high prepayment speeds as market rates are more
often below 6 percent than above.

However, 6.5-percent bond, despite having the highest weighted-average coupon of
7.21 percent, has a lower projected prepayment speed. Presumably, the high
interest rates in this pool are explained by higher credit risk or less
sophistication among borrowers. Since borrowers with higher credit risk or less
sophistication are unable or less likely to refinance, their projected
prepayment speed is also lower.

### Short Question 2 Part H

> Why do you think for some coupons the projected long-term CPRs are higher than
> the projected 1-month and 3-month speeds, while for other coupons they are
> lower?

For lower-coupon bonds, the short-term prepayment projection speeds are lower
than the long-term projections because when the coupon rate is near a minimum,
it is unlikely that it will fall further. Thus, most of the prepayment is
explained by borrowers exiting the mortgage to move homes. Since almost no
borrowers will leave their home in the first few months, the short-term
prepayment projection is low; however, the share of borrowers moving increases
in the long term.

For higher-coupon bonds, the short-term projections are higher than the
long-term ones because when the coupon rate is near a maximum, it is likely that
it will fall soon. Borrowers may enter these high-rate mortgages expecting to
refinance when rates normalize.

For bonds with coupons that are neither near a minimum nor a maximum, the short-
and long-term projects are close together, but the long-term projections tend to
be lower since it is still possible for interest rates to rise in the long-term.

## Short Question 2: Default risk based on mortgage observable characteristics

The mortgages below are ranked in descending order of credit risk, from riskiest
to least risky.

|    | CLTV | FICO | DTI | Lien | Income documentation |
|----|------|------|-----|------|----------------------|
| d. | 90% | 620 | 36 | Second | None |
| b. | 90% | 660 | 36 | Second | Partial |
| g. | 80% | 680 | 34 | Second | Partial |
| f. | 80% | 680 | 34 | First | Partial |
| e. | 80% | 680 | 32 | First | Partial |
| a. | 80% | 680 | 32 | First | Full |
| c. | 70% | 730 | 28 | First | Full |

## Problem 1: CMO spreadsheet

