# Assignment 1

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

$$Q_{36}=(1-0.5\%)^{12}\cdot(1-1.5\%)^{36}\approx 65.5\%.$$

## Short Question 2

> Assume the mortgage interest deduction is abolished.

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
value ($V=1$):

$$C=\text{pmt}\left(r=\frac{4.5\%}{12},n=26\times 12,V=1\right)\approx 0.5443\dots\%.$$

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
