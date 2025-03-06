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
> you think would happen to the price of a fixed-rate passthrough
> mortgage-backed security (MBS) with a 6% coupon? What about an MBS with a 3%
> coupon?

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

![Comparison of prepayment assumptions on price-yield relation](https://github.com/ishanpranav/finc-2339-real-estate-capital-markets/blob/master/images/assignment-2.jpeg?raw=true "Comparison of prepayment assumptions on price-yield relation")

__Comparison of prepayment assumptions on the price-yield relation.__

## Short Question 4

We will reference
["Comradely capitalism"](https://www.economist.com/briefing/2016/08/20/comradely-capitalism)
published in *The Economist*,
["The Mortgage Market's $1 Trillion Pocket of Worry"](https://www.wsj.com/articles/the-mortgage-markets-1-trillion-pocket-of-worry-1484827201?msockid=1160542f41e96ed30ee645d040076fd7)
by AnnaMaria Andriotis, published in *The Wall Street Journal*, and
["The Case For Housing Finance Reform"](https://www.federalreserve.gov/newsevents/speech/powell20170706a.htm),
a speech delivered by Jerome Powell.

### Short Question 4 Part A

> What does "Comradely capitalism" refer to? How well capitalized is the
> mortgage system compared to banks?

"Comradely capitalism" refers to the administrative role of the government in
the mortgage market. *The Economist* argues that "the supply of mortgages in
America has an air of distinctly socialist command-and-control about it" and
that there should be a path for government-sponsored enterprises (GSEs) like
Fannie Mae and Freddie Mac to be released from conservatorship. Currently, GSEs
play a cdentral role in packaging and guaranteeing home loans. This hybrid
structure integrates state support into the market economy, making the mortgage
market heavily reliant on the government.

### Short Question 4 Part B

> What are estimates of potential losses to Fannie Mae, Freddie Mac and the
> Federal Housing Administration (FHA) in another housing crash?

If there were another severe housing downturn like that of the Global Financial
Crisis (GFC), the projected losses for Fannie, Freddie, and the FHA would range
from 2 to 4 percent of U.S. gross domestic product, or between $300 and $600
billion at the time of the article's publication.

Taxpayers would bear these losses, since the government explicitly or implicitly
guarantees most of the risk associated with these mortgage institutions.

### Short Question 4 Part C

> What is troubling about FHA loans and nonbank lenders?

FHA loans and nonbank lenders are exposed to graeter financial risk since they
tend to extend mortgages with higher loan-to-value ratios and to borrowers with
lower credit scores.

Nonbank lenders have less stringent capital and liquidity requirements, since
they are not subject to the same post-GFC regulations as the banking sector.

It is troubling that these institutions are exposed to riskier mortgages yet
have less secure balance sheets—and that the American taxpayers are the
equityholders who bear this risk.

### Short Question 4 Part D

> Where does Jerome Powell chiefly lay the blame for the housing finance boom
> (and presumably, the subsequent crash) of the 2000s?

Jerome Powell blames bad incentives in the financial system, specifically for
the GSEs and private-label securitizations. Although the government provided no
legal guarantee on mortgages owned by Fannie and Freddie, financial markets
"priced in" an implicit guarantee on the assumption that these institutions were
"too big to fail." As a result, underwriting standards declined, due diligence
was substandard or nonexistent, and the housing market, along with associated
capital markets, boomed with the influx of new mortgages.

Ultimately, the relaxation of underwriting standards generated short-term
profits at the cost of total economic collapse.

### Short Question 4 Part E

> Would you reason that government-sponsored or guaranteed (e.g. FHA)
originations make up a bigger or smaller share of total residential mortgage
originations after a disaster or crisis hits, for example in Puerto Rico before
compared to after Maria?

After a crisis, we expect that government-sponsored or guaranteed originations
make up a larger share of total resedential originations.

After a disaster like Maria in Puerto Rico, private lenders would likely deem
the region too risky and be less eager to originate mortgages or abandon the
market entirely.

Meanwhile, GSEs would be responsible for recovering the local economy and would
subsidize housing in affected areas. The mandate of GSEs is to satisfy mortgage
demand where private markets fail to do so, so their share of originations would
increase.

## Problem 1

> Your hedge fund owns an MBS pool backed by fully-amortizing fixed-rate
> mortgages (FRMs) with a coupon interest rate of 4.5%, and a remaining maturity
> of 26 years. Based on your analysis of past prepayment data, you currently
> expect all the mortgages in the pool to prepay fully in five years’ time. The
> market interest rate (used for discounting future cash flows) is 3.0%.
> Mortgage payments are monthly, as usual.

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

## Problem 2

> Consider an agency MBS pool consisting of $300M of 15 year FRMs with a
> mortgage coupon rate of 4.5%. Mortgage payments are monthly. Assume a
> servicing and guarantee fee of 50bp per year (combined) for this pool.
>
> Assume that this pool prepays at 200% PSA (benchmark of the Public Securities
> Association) throughout its life.

### Problem 2 Part A

> What is the net coupon rate paid to MBS investors?

The net MBS coupon payment is $4.5\%-0.5\%=4.0\%.$

### Problem 2 Part B

> What is the SMM on this pool in the first month? What is the peak SMM for this
> pool over its life?

The single-month mortality rate (SMM) is the fraction of the mortgage pool that
is prepaid in full during a given month.

We can compute the CPR for the first month and use it to derive the SMM.

In month $1$, the CPR is the PSA level multiplied by the factor
$\frac{1\times 0.2}{100}$, so the CPR is
$200\%\times\frac{1\times 0.2}{100}=0.4\%$.

In the first month, the SMM is $1-(1-0.4\%)^{\frac{1}{12}}\approx 0.0334\%.$

Using the PSA prepayment model, the conditional prepayment rate (CPR) peaks at
month 30. We can compute the peak CPR, then derive the peak SMM from it.

In month $30$, the CPR is the PSA level multiplied by the factor
$\frac{30\times 0.2}{100}$, so the CPR is
$200\%\times\frac{30\times 0.2}{100}=12\%.$

The peak SMM is $1-(1-12\%)^{\frac{1}{12}}\approx 1.0596\%.$

### Problem 2 Part C

We reference the [spreadsheet](https://ishanpranav.github.io/finc-2339-real-estate-capital-markets/assignment-2.xlsx)
attached, which indicates the total amount of principal payments, interest
payments, servicing and guarantee payments, and prepayments, for each month over
the life of the pool.

### Problem 2 Part D

> Assuming a discount rate of 5% per year, what is the NPV of this mortgage pool?
> Is this pool trading at a discount or a premium? Why?

Assuming a discount rate of 5 percent, the NPV of investor cash flows is
$286,550,548.43, or about $287M.

Since the MBS investor coupon rate (4%) is less than the discount rate (5%), we
know that this mortgage pool is trading at a discount.

### Problem 2 Part E

> If the discount rate falls to 4%, what is the new NPV of the pool, assuming
> there is no change in the SMM.

Since the MBS investor coupon rate (4%) is equal to the discount rate (4%), this
mortgage is trading at par. Thus, the NPV of investor cash flows is exactly
$300M. Recomputing the NPV confirms this result.

### Problem 2 Part F

> Do you think this assumption that the SMM does not change is realistic? Why?

No, the assumption that the SMM does not change is unrealistic. The change in
the discount rate from 5% to 4% corresponds to a decline in the borrower's
interest rate. As a result, prepayment would increase as borrowers prefer to
refinance at the lower rate.

The SMM would increase as a result of increased prepayment.

### Problem 2 Part G

> Now (under the discount rate assumption in Part D) assume that all borrowers
> that have not prepaid within the first five 5 years default on their mortgages
> at year 5 (i.e. after 60 months). What is the credit loss to you as an
> investor? Would these defaults be good news or bad news for you, or would you
> be indifferent? Explain intuitively (no calculations required).

Since this is an agency MBS pool, the mortgages are guaranteed by a GSE. As an
investor, there is no credit risk or credit loss as a result of mortgage
defaults.

The defaults would be neither good news nor bad news (we would be indifferent),
as the cash flows do not change: We assume that agency MBS investors receive all
the scheduled principal and interest payments.

If instead we assume that we receive the principal payments immediately upon
default, this would be good news. This is because the agency MBS is trading at a
discount (below par) and we are receiving the full (par) amount, which increases
our NPV. It is especially good news because we can now reinvest our returned
capital at a higher interest rate.

As investors, the cost of credit risk is included in the guarantee fee: Our
cash flows are insured against default.

### Problem 2 Part H

> Calculate the new NPV of the pool under the assumption in part G, assuming a
> discount rate of 5% per year. Assume for simplicity that face value of the
> mortgages that default is returned to the investor without any time lag.
> Compare your answer to what you calculated in part D, and confirm that it is
> consistent with your answer and explanation from part G above.

In Part G, we assumed that investors receive their scheduled payments of
interest and principal upon default.

In Part H, we assume that the full principal amount is returned immediately upon
default. This means that the second case of Part G applies: Since the MBS is
trading at a discount to par, our NPV increases when borrowers default because
we receive par.

Based on the second sheet of our
[spreadsheet](https://ishanpranav.github.io/finc-2339-real-estate-capital-markets/assignment-2.xlsx),
we notice that in the default case the NPV of investor cash flows increases to
$289,950,264.51, or about $290M, up from $287M with no defaults. This is because
our cash flows arrive sooner and our discount rate is higher than our coupon
rate.

The news is especially good since we can now reinvest our returned capital at
the higher interest rate.
