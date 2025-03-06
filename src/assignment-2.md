# Assignment 2

Ishan Pranav, Yerim Ryoo, and Pavan Chand

March 6, 2025

Professor Arpit Gupta

FINC 2339 Real Estate Capital Markets

## Short Question 1

> Consider a pool of mortgages, originated three years ago. Prepayment on this
> pool of mortgages ran at a single-month mortality (SSM) of 0.5% over the first
> 12 months, and then an SMM of 1.5% over months 13-36. What is the survival
> factor for this pool?

In month $t$, the survival factor $Q_t$ is a function of the SMMs for months $1$
to $t$:

$$Q_{36}=(1-0.5\%)^{12}\cdot(1-1.5\%)^{24}\approx 65.5\%.$$

## Short Question 2

> Assume the mortgage interest deduction is abolished.

### Short Question 2 Part A

> What do you think would happen to mortgage prepayment speeds, and why?

If the mortgage interest deduction were abolished, mortgage prepayment speeds
would likely increase. Reducing or eliminating the mortgage interest deduction
increases the effective coupon rate paid by borrowers. As a result, mortgage
debt would become less attractive, and there would be a greater incentive to
extinguish the debt.

Relative to other investment opportunities, mortgage debt would become more
expensive, so borrowers may prefer to use their capital to pay it down before
purchasing assets.

### Short Question 2 Part B

> Assume current mortgage rates are at 4%. The day of the announcement, what do
> you think would happen to the price of a fixed-rate passthrough MBS with a 6%
> coupon? What about an MBS with a 3% coupon?

The price of a fixed-rate passthrough MBS with a 6-percent coupon would decline:
Its coupon rate (6%) is above-market (4%). Eliminating the mortgage interest
deduction encourages prepayment, so the premium on the MBS falls. This is an
example of contraction risk.

The impact on the price of an MBS with a 3-percent coupon is uncertain. Since
the coupon rate (3%) is below-market (4%), borrowers are less likely to prepay.
There may be some borrowers who prepay in response to the loss of the mortgage
interest deduction. However, the amount of prepayment is limited since borrowers
prefer to remain locked in to the lower rate. This is an example of extension
risk for the lender. The impact on the price of this MBS is likely minimal.

The 3-percent coupon MBS is less sensitive to the tax-law change than the
6-percent coupon MBS.

### Short Question 2 Part C

> What do you think would happen to the size of new loans that are originated
> after the announcement? Going forward, would this likely increase or decrease
> the interest rate sensitivity of prepayments?

New loans that originate after the announcement would likely be smaller than
similar loans that originated before the announcement. Without the mortgage
interest deduction, borrowers can afford smaller mortgage payments for the same
income and budget levels.

Yes, going forward, the interst rate sensitivity of prepayments would increase.
With the deduction, borrowers are only exposed to a fraction of the change in
interest rate (that is, the after-tax interest rate $r(1-\tau)$). Without the
mortgage interest rate deduction, borrowers are completely exposed to
fluctuations in the interest rate ($r$). As a result, they are more
rate-sensitive and more motivated to change their prepayment behavior in
response to changes in the interest rate.

## Short Question 3

> Suppose you own an MBS pool with a coupon of 6%. Plot a graph of the value of
> the MBS (on the $y$-axis) against current market yields (on the $x$-axis),
> under 3 different assumptions about the prepayment behavior of the borrowers
> in the pool:
>
> (a) They exhibit typical prepayment behavior, as observed empirically.
>
> (b) They hardly ever prepay, and prepayments are not at all sensitive to
> interest rates. Assume the CPR is 2% no matter where current rates are.
>
> (c) They are perfectly efficient prepayment robots: All of them prepay as soon
> as yields drop below the coupon rate, and none of them prepay when yields are
> above the coupon rate.

![Comparison of prepayment assumptions on price-yield relation](https://github.com/ishanpranav/finc-2339-real-estate-capital-markets/blob/master/images/assignment-2.png?raw=true "Comparison of prepayment assumptions on price-yield relation")

## Short Question 4

## Problem 1

> Your hedge fund owns a mortgage-backed securities (MBS) pool backed by
> fully-amortizing fixed-rate mortgages with a coupon interest rate of 4.5%, and
> a remaining maturity of 26 years. Based on your analysis of past prepayment
> data, you currently expect all the mortgages in the pool to prepay fully in
> five years’ time. The market interest rate (used for discounting future cash
> flows) is 3.0%. Mortgage payments are monthly, as usual.

### Problem 1 Part A

> What is the market price of the pool described above, expressed as a
> percentage of par value?

First, we determine the regular monthly payment as a percentage of the par
value ($V=100\%$):

$$C=\text{pmt}\left(r=\frac{4.5\%}{12},n=26\times 12,V=100\%\right)\approx 0.5443\dots\%.$$

We also determine the remaining principal balance at the time of prepayment:

$$V_5=\text{pv}\left(r=\frac{4.5\%}{12},n=(26-5)\times 12,C=0.5443\dots\%\right)\approx 88.6320\dots\%.$$

The market price is the sum of the present value of five years' worth of
payments, plus the present value of the remaining principal balance in five
years.

$$\begin{align*}
V_0&=\text{pv}\left(r=\frac{3.0\%}{12},n=5\times 12,C=0.5443\dots\%\right)\\&+\text{pv}\left(r=\frac{3.0\%}{12},n=5\times 12,C=0,V_5=88.6320\dots\%\right)\\
&\approx 106.5923\dots\%\\
&\approx 106~\frac{19}{32}\%.\
\end{align*}$$

The market price is 106-19.

### Problem 1 Part B

> Imagine that Quicken’s new Rocket Mortgage app becomes widely available to
> borrowers and sends alerts to them continuously prodding or “nudging” them to
> refinance. As a result, 10% of the borrowers in the pool refinance their
> mortgages via Quicken immediately, and the other 90% are now expected to
> prepay their mortgages in three years’ time instead of five years’ time. What
> gain or loss will your hedge fund experience, expressed as a percentage of the
> prior market value of your MBS investments?

The immediate payments amount to 10% of the remaining balance.

The new cash flow is the payment received from the 90% of the mortgages which
survived the initial prepayment:

$$C=\text{pmt}\left(r=\frac{4.5\%}{12},n=26\times 12,V=90\%\right)\approx 0.4899\dots\%.$$

Again, we determine the remaining principal at the time of prepayment:

$$V_3=\text{pv}\left(r=\frac{4.5\%}{12},n=(26-3)\times 12,C=0.4899\dots\%\right)\approx 84.1388\dots\%.$$

The market price is the sum of the immediate prepayments (10 percent of the par
value), the present value of three years' worth of payments, and the present
value of the remaining principal balance in three years.

$$\begin{align*}
V_0'
&=10\%\\
&+\text{pv}\left(r=\frac{3.0\%}{12},n=3\times 12,C=0.4899\dots\%\right)\\&+\text{pv}\left(r=\frac{3.0\%}{12},n=3\times 12,C=0,V_5=84.1388\dots\%\right)\\
&\approx 93.7516\dots\%\\
&\approx 93~\frac{24}{32}\%.\
\end{align*}$$

The hedge fund will experience a loss of about 12 percent.

$$\left(\frac{93.7516\%}{106.5923\%}\right)-1\approx -12.0466\dots\%.$$

## Problem 1 Part C

> What kind of risk does the scenario in Part B illustrate? Briefly explain the
> economic intuition for why your fund experienced a gain or loss in part B.

The scenario in Part B illustrates prepayment risk.

In Part B, the fund experienced a loss because the borrowers prepaid their
mortgages during an interest-rate environment where the coupon rate (4.5
percent) was higher than the market interest rate (3.0 percent). This cut into
the lender's profit.

When interest rates fall, the borrower's option to prepay without penalty
increases in value. When borrowers exercise that option, the mortgage owner
suffers.

### Problem 1 Part D

> Go back to the original information in the question (ignoring Parts B and C).
> Imagine that market interest rates suddenly rise from 3.0% to 5.0%. What gain
> or loss will your hedge fund experience, expressed as a percentage of the
> original market value of your mortgage investment, assuming that borrower
> prepayment behavior does not change?

$$\begin{align*}
V_0'&=\text{pv}\left(r=\frac{5.0\%}{12},n=5\times 12,C=0.5443\dots\%\right)\\&+\text{pv}\left(r=\frac{5.0\%}{12},n=5\times 12,C=0,V_5=88.6320\dots\%\right)\\
&\approx 97.9056\dots\%\\
&\approx 97~\frac{29}{32}\%.\
\end{align*}$$

The hedge fund will experience a loss of about 8 percent:

$$\left(\frac{97.9056\%}{106.5923\%}\right)-1\approx -8.1495\dots\%.$$

### Problem 1 Part E

> Imagine that your hedge fund was leveraged 8 to 1 (i.e., only one-eighth of
> the assets are financed by equity). What would be the effect of the scenario
> in Part D on the market value of the equity in your hedge fund?

The impact of a gain or loss would be amplified by the fund’s leverage factor.

In this case, the loss of 8.1495% would be amplified by the leverage factor of
8, leading to an equity loss of 65.1962%.

### Problem 1 Part F

> What kind of risk does the scenario in Part D illustrate?

The scenario in Part D illustrates interest-rate risk.

The market interest rate can fluctuate, whereas the coupon rate is fixed. Thus,
the present value of the MBS pool fluctuates with changes in this discount rate.

Since hedge funds are leveraged (as illustrated in Part E), interest-rate risk
can result in a significant loss (or gain) for equity investors.

### Problem 1 Part G

> In practice, if the interest rate shock in Part D occurred, what would you
> expect to happen to borrower prepayment behavior? Would this change in
> behavior be good news or bad news for you as an MBS investor?

In Part D, the sudden increase in interest rates can be categorized as an
extension risk. Extension risk is a form of prepayment risk where the increase
in interest rates leads to a fall in prepayments.

As market interest rates rise, borrowers are less willing to refinance their
mortgages, so prepayments decrease. The lender is locked into a fixed coupon
rate (in Part D, 4.5 percent) that is less than the market interest rate (3.0
percent), so the MBS trades at a discount.

The change in prepayment behavior is bad news for an MBS investor,
since it causes the value of the MBS to fall more quickly than it otherwise
would in response to the increase in interest rates.

### Problem 1 Part H

> Describe a scenario where liquidity risk might cause a change in value in your
> investment. Would the liquidity risk of your investment likely be higher if
> this was an agency MBS pool, or a nonagency MBS pool? Briefly explain your
> logic.

Suppose there were a global financial crisis during which people lost confidence
in the performance of mortgages. Demand for MBS would fall, and people would
invest in safer investments, such as U.S. Treasury bonds. If demand for MBS is
low enough, it may be difficult to obtain a fair price, and MBS investors may
have to liquidate their positions at a discount to present value.

The liquidity risk of our investment would be higher if it was a non-agency,
since it is not backed by a government agency. Investments in agency MBS, like
Fannie Mae and Freddie Mac, have lower risk since they are backed by the U.S.
government, whereas non-agency MBS pools are more exposed to market conditions.
During a crisis, the market for agency MBS would likely remain more liquid
because of their government backing.
