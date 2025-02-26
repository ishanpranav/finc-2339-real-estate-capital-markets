# Assignment 1

Ishan Pranav, Ellen Ryoo, and Pavan Chand

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

There would be no change.

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
