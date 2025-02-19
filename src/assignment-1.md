# Assignment 1

Ishan Pranav and Ellen Ryoo

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

$$V=\frac{\$4000.00~\text{per month}}{6.24\%~\text{per year}}\cdot\frac{12~\text{months}}{1~\text{year}}\approx 769230.76.$$

With a 5/1 interest-only ARM, Jennifer will be able to borrow at most
$769,230.76.

### Short Question 2 Part B

> What would be the size of her mortgage if she took out the worst of the three
> options given her objective?

The worst option is the 30-year FRM, since it has the highest interest rate and
requires principal repayment in installments.

$$V=\text{pv}\left(r=\frac{6.93\%}{12},n=30\times 12,C=\$4000\right)\approx 605502.83.$$

With a 30-year FRM, Jennifer will be able to borrow at most $605,502.83.

## Short Question 3

> After graduating from NYU Stern, you join the commercial real-estate
> originations business of a large commercial bank. In your first deal, your
> bank originates a $35M fixed rate commercial mortgage with a 4.75% annual
> interest rate, 10-year term, 30-year amortization period, and monthly
> payments. What is the size of the balloon payment due on this mortgage at
> maturity?
