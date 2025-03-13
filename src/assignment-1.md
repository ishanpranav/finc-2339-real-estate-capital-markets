# Assignment 1

Ishan Pranav, Yerim Ryoo, and Pavan Chand

February 27, 2025

Professor Arpit Gupta

FINC 2339 Real Estate Capital Markets

## Short Question 1

> Property mogul Ronald Prumt considers buying a multi-family property at a cap
> rate of 6 percent. Consider the simplified user cost model and
> assume that the after-tax mortgage rate at which Prumt can finance the
> purchase is 6 percent per year and the maintenance expenditure is 2 percent
> per year. What is the minimum expected future price appreciation such that
> this would be a winning deal for Prumt?

For a given period $t$, let $R_t$ denote rental income and $P_t$ denote price.
Note $R_0/P_0=6\%$. Let $r(1-\tau)=6\%$ denote the mortgage rate after applying
tax rate $\tau$. Let $m=2\%$ denote the maintenance rate.

The simplified user cost model gives the expected price appreciation.

$$\frac{R_0}{P_0}=r(1-\tau)+m-\mathbb{E}\left(\frac{P_1}{P_0}-1\right).$$

$$\begin{align*}
\mathbb{E}\left(\frac{P_1}{P_0}-1\right)&=r(1-\tau)+m-\frac{R_0}{P_0},\\
&=6\%+2\%-6\%,\\
&=2\%.
\end{align*}$$

Intuitively, since rental income covers the mortgage interest expense, the
minimum expected price appreciation is 2 percent (to cover the maintenance
expense).

## Short Question 2

> Your good friend Jennifer is very optimistic about the housing market and
> believes that house prices can only go up. As a consequence, she wants to buy
> the most expensive home she can possibly afford, with the idea of selling it
> at a profit in a few years. She has $4,000 per month that she can spend on the
> mortgage payment (and her parents offered to help out with the down payment).
> Jennifer’s lender has offered her three types of mortgages: a standard 30 year
> fixed-rate mortgage (FRM), a 5/1 adjustable-rate mortgage (ARM) with standard
> amortization, and a 5/1 ARM with a 5-year interest-only period. Jennifer asks
> you for help.

### Short Question 2 Part A

> For simplicity, ignore taxes and tax deductions for this question.

> Which mortgage type do you think is best given her objective?

Jennifer should choose the 5/1 ARM with a 5-year interest-only period.

Since Jennifer intends to remain in the mortgage for at most 5 years, she is
indifferent between a fixed rate and a rate that adjusts 1 time per year after
the first 5 years. Meanwhile, lenders, whose liabilities are exposed to
interest-rate risk, may offer a lower rate on ARMs to incentivize them.

In an interest-only mortgage, no part of Jennifer's $4,000 payment contributes
to principal. Thus, an interest-only mortgage allows her to buy a more expensive
property.

> Find the current interest rates on FRMs and 5/1 ARMs. Assume both the 5/1 ARMs
> have this same interest rate. Based on this information, what is the size of
> the mortgage she would receive under the option you recommended?

We will use data on the current mortgage interest rates from
[Bankrate.com](https://www.bankrate.com/mortgages/mortgage-rates/).

| February 19, 2025 | 30-year fixed | 5/1 ARM |
|-------------------|--:|--:|
| National average interest rate | 6.93% | 6.24% |

Let $V$ denote the maximum loan amount.

$$V=\frac{\$4000.00~\text{per month}}{6.24\%~\text{per year}}\cdot\frac{12~\text{months}}{1~\text{year}}\approx\$769230.76.$$

With a 5/1 interest-only ARM, Jennifer will be able to borrow at most
$769,230.76.

### Short Question 2 Part B

> What would be the size of her mortgage if she took out the worst of the three
> options given her objective?

The worst option is the 30-year FRM, since it has the highest interest rate and
requires principal repayment in installments.

$$V=\text{pv}\left(r=\frac{6.93\%}{12},n=30\times 12,C=\$4000\right)\approx \$605502.83.$$

With a 30-year FRM, Jennifer will be able to borrow at most $605,502.83.

## Short Question 3

> After graduating from NYU Stern, you join the commercial real-estate
> originations business of a large commercial bank. In your first deal, your
> bank originates a $35M fixed rate commercial mortgage with a 4.75% annual
> interest rate, 10-year term, 30-year amortization period, and monthly
> payments. What is the size of the balloon payment due on this mortgage at
> maturity?

First, we determine the regular monthly payment:

$$C=\text{pmt}\left(r=\frac{4.75\%}{12},n=30\times 12,V_0=\$35~\text{million}\right)\approx\$182576.57.$$

__Future-value method.__

The balloon payment is the remaining unamortized principal (that is, the future
value) of the loan after 10 years (that is, 120 months).

$$V_{120}=\text{fv}\left(r=\frac{4.75\%}{12},n=10\times 12,C,V_0=\$35~\text{million}\right)\approx\$28252846.22.$$

The balloon payment is about $28 million.

__Present-value method.__

The balloon payment can also be expressed as the present value of the remaining
cash flows amortized over months 121 to 360.

$$V_{120}=\text{pv}\left(r=\frac{4.75\%}{12},n=20\times 12,C\right)\approx\$28252846.22.$$

The results match.

## Short Question 4

> Suppose two houses sold in your neighborhood in the following years:

|            | Year | Price | Year | Price |
|------------|------|------:|------|------:|
| Property 1 | 2017 | $320k | 2018 | $400k |
| Property 2 | 2017 | $300k | 2019 | $360k |

### Short Question 4 Part A

> Using the repeat-sales methodology, what is the estimated appreciation in
> house prices for this area between 2018 and 2019?

We can estimate $r$, the appreciation from 2018 to 2019, using a
no-arbitrage argument.

$$\frac{\$360000}{\$300000}=\frac{\$400000}{\$320000}\cdot(1+r).$$

$$1+r=0.96\Rightarrow r=-4\%.$$

The estimated change in house prices from 2018 to 2019 was -4%.

### Short Question 4 Part B

> If both properties sold initially in 2010 rather than 2017 and these were the
> only sales over that period, how would your answer to Part A change?

The result would be the same: -4% from 2018 to 2019.

Changing the initial year the properties were sold to 2010 only shifts the
periods from 2017-2018 and 2018-2019 to 2010-2018 and 2018-2019.

For this reason, the result from Part A still applies. The only difference is
the price appreciation prior to 2018. Instead of covering one year, the pre-2018
price appreciation now covers 8 years.

## Problem 1: Mortgage interest deduction

> Congress has passed legislation lowering the mortgage interest deduction limit
> from $1,000,000 to $750,000.

### Problem 1 Part A

> What is the mortgage interest deduction? Which types of mortgage borrowers
> benefit most from it, and why?

* The mortgage interest deduction lets taxpayers deduct the interest and points
  paid on qualified mortgages.
  * The deduction applies to primary and secondary residences, but not
    investment properties.
  * There is a limit on the total amount of debt ($750,000 for new mortgages).
* The deduction benefits high-income, recent homebuyers in high-tax states.
  * Higher-income earners and residents of higher-tax states have higher
    marginal tax rates and thus benefit more from deductions.
  * Earlier mortgage payments contain more interest, so the deduction begins at
    its peak, and declines thereafter.
* The Tax Cuts and Jobs Act (2017) makes itemized deductions, including this
  one, much less attractive relative to the standard deduction.

### Problem 1 Part B

> The mortgage interest deduction is often criticized by economists and others.
> What are some of the key problems or issues which are highlighted by these
> critics? Can you think of any counterarguments?

* _Economists' criticism:_ the mortgage interest deduction is regressive,
  disproportionately benefitting wealthy households.
  * _Our rebuttal:_ middle-class homeowners in high-tax states still rely on the
    deduction to subsidize borrowing.
* _Economists' criticism:_ in practice, the deduction reduced the homeownership
  rate since the tax benefit becomes capitalized in the house price.
  * _Our rebuttal:_ since the Tax Cuts and Jobs Act increased the standard
    deduction, the mortgage interest deduction is most relevant in high-cost
    markets. Luxury markets would face the biggest impact.

Source: [Why Economists Don't Like the Mortgage Interest Deduction - Federal Reserve Bank of St. Louis](https://www.stlouisfed.org/open-vault/2018/may/why-economists-dont-like-mortgage-interest-deduction)

### Problem 1 Part C

> Thinking about the user cost model we studied in class, what effect would
> cutting or eliminating the mortgage interest deduction have on the cap rate
> for residential real estate. Would this effect be larger when interest rates
> are low or when rates are high? Explain.

In the existing model, the cap rate depends on $r(1-\tau)$. Without a mortgage
interest deduction, the caprate would be $r$. Since $r>r(1-\tau)$ when $\tau>0$,
the cap rate increases. The difference is amplified when the interest rate is
high, since eliminating the deduction effectively scales up the interest rate.

## Problem 2: Fixed-rate mortgage

> You take out a 15-year fixed-rate mortgage for $500,000, and buy down the
> interest rate by purchasing two points. After the points, the interest rate
> you agree to is 3.25% per annum. You subsequently retain this mortgage for 3
> years, before prepaying it.

### Problem 2 Part A

> What is the monthly payment on this mortgage? How much of the initial payment
> is interest, and how much is principal?

$$C=\text{pmt}\left(r=\frac{3.25\%}{12},n=15\times 12,V_0=\$500000\right)\approx\$3513.34.$$

Of the initial payment, $\frac{3.25\%}{12}\times\$500000\approx\$1354.17$ is
interest, so the remaining $\$3513.34-\$1354.17\approx\$2159.18$ is repayment of
principal.

### Problem 2 Part B

> Over the three years, what is the total of all the interest payments you make
> on this loan? What is the total value of the principal payments?

The total of all payments is
$3\cdot 12\cdot C=3\cdot 12\cdot\$3513.34\approx\$126410.38$.

The remaining value of the loan is its future value in 3 years (36 months):

$$V_{36}=\text{pv}\left(r=\frac{3.25\%}{12},n=3\times 12,V_0=\$500000\right)\approx\$418469.87.$$

Thus, the total value of the principal payments is $\$500000-418469.87=\$81530.13$.

The remaining $\$126410.38-\$81530.13=\$44950.25$ is the total value of the
interest payments.

### Problem 2 Part C

> Given that you paid off the loan after three years, would you have been better
> off (in terms of the effective interest rate) if you hadn’t paid points but
> taken a 3.75% interest rate? How would this answer change if you had held the
> loan until maturity instead?

Since the loan was paid off after 3 years, a higher interest rate makes more
sense than paying points, since it results in a lower effective interest rate
over the short holding period.

If the loan were held to maturity, the compounding effect of the larger interest
rate overcomes the upfront point payment, so it would make more sense to buy
down the interest rate with points.

### Problem 2 Part D

N/A.

### Problem 2 Part E

> What types of borrowers would generally not want to buy points on a fixed-rate
> mortgage?

Borrowers who intend to exit the mortgage early (refinance to a lower rate or
prepay), prefer not to buy points on a fixed-rate mortgage.

### Problem 2 Part F

> Are prepayment penalties common for this type of loan?

No, prepayment penalties are not common for prime residential mortgages.
However, refinancing transaction costs generally create friction for borrowers
upon prepayment.

Prepayment penalties were common for subprime borrowers during the mortgage boom
and are still present in the commercial mortgage market.

## Problem 3

### Problem 3 Part A

> Notice that the “zestimate” – Zillow’s best estimate of the house price –
> jumps in July 2018. Can you figure out why Zillow’s formula to estimate prices
> would predict such a large increase? Do you think the variable that accounts
> for this increase should be in their formula to estimate the price?

In July 2018, the "zestimate" jumps from $763 thousand to $1.2 million. This is
because the home was listed for sale for $1,290,000 that month. Including
listing price in the "zestimate" is questionable because it creates a circular
feedback loop that introduces bias.

### Problem 3 Part B

> Suppose that John put 20% down and paid $1.3 million on the property. Using
> the estimate for 30 FRM rates you gathered in Short Question 2, estimate the
> monthly payment for a 30-year fixed-rate mortgage on this property.

$$C=\text{pmt}\left(r=\frac{6.93\%}{12},n=12\times 30,V_0=80\%\times\$1.3\text{ million}\right)\approx\$6870.32.$$

The monthly payment is about $6,870.32.

### Problem 3 Part C

> Suppose that John has the money to pay for the property in cash, or get a
> mortgage. Factoring in the interest deduction (at a 37% tax bracket); how much
> will John have paid in total for the mortgage after 30 years?

We assume that John claims itemized deductions in all years. For simplicity, we
also assume that ther eis no limit on the loan balance for the purpose of the
mortgage interest deduction.

The total payments are $6870.32\times 360$, or about $2,473,316.27.

Thus, the total interest payments are $2473316.27-1040000$, or about $1,433,316.27.

After the mortgage interest deduction, the cost of borrowing is $1433316.27\times(1-37\%)$, or about $902,989.25.

The total cash outflows are $1,942,989.25, including payments of principal and
interest, net of tax deductions.

### Problem 3 Part D

> If John could instead reinvest the cash somewhere else – what rate of return
> would John need on the alternate investment for it to make sense to get the
> mortgage instead of paying fully in cash?

John should invest if the income from investing equals the net interest expense
on the mortgage:

$$r=\left(\frac{\$1040000+\$902989.25}{\$1040000}\right)^{\frac{1}{360}}-1\approx(0.174\%\times 12)\approx 2.09\%.$$

If John can invest at a 2.09% APR, he will take the mortgage.

### Problem 3 Part E

> Suppose the property has a $14,000/year flood insurance requirement if the
> property has a mortgage. How does your answer to Part D change?

The total cost of flood insurance is $420,000, so the total cost of the mortgage
increases to $1,322,989.25.

Still, John should invest at a rate where investment income equals net
investment expense:

$$r=\left(\frac{\$1040000+\$1322989.25}{\$1040000}\right)^{\frac{1}{360}}-1\approx(0.228\%\times 12)\approx 2.74\%.$$

Now John must invest at a 2.74% APR.

### Problem 3 Part F

> Should John get the mortgage?

Yes. The 30-year Treasury rate is above John's required rate of return. He can
obtain a long-term mortgage and collect arbitrage profits by investing in
credit-risk-free securities with a higher rate of return.
