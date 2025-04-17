# Assignment 4

Ishan Pranav, Yerim Ryoo, and Pavan Chand

April 17, 2025

Professor Arpit Gupta

FINC 2339 Real Estate Capital Markets

## Short Question 1

> Holding all else equal, what would you expect to happen to the AAA
> subordination on a nonagency mortgage-backed security (MBS) deal if there were
> fewer loans in the deal? Why? How is this related to differences in credit
> ratings for single asset or single borrower (SASB) versus conduit
> commercial-mortgage-backed security (CMBS) deals?

Holding all else equal, suppose there are fewer loans, rather than more loans,
in a non-agency MBS deal: The AAA subordination level is higher in this
situation.

Fewer loans implies less diversification and more risk, since if an individual
loan defaults, it will have a larger impact on the performance of the entire MBS
pool. For this reason, the AAA subordination level is higher, since the AAA
tranche needs more insulation from the potentially devastating losses that one
or a few defaults could cause. Given the higher risk in this pool, ratings
agencies would require more credit subordination for the same AAA rating.

This concept also helps explain differences between credit ratings for SASB and
conduit CMBS deals. Single asset and single borrower deals exhibit the same lack
of diversification as a pool with a few loans, so they are more exposed to
asset-specific risk. Meanwhile, conduit CMBS deals consist of many smaller
loans, offering more diversification and lower risk. Thus, compared to conduit
CMBS deals, SASB deals should have greater AAA subordination.

## Short Question 2

> Consider a single-loan CMBS deal of size $1,000M, with a B-piece of $100M. The
> loan has become delinquent and been transferred to special servicing. Expected
> losses are $150M if the property is foreclosed on. If the loan is
> restructured, there is a 30% chance the borrower will start performing,
> reducing losses to zero, but a 70% chance that final losses will rise to
> $300M.

### Short Question 2 Part A

> What should the CMBS investors do to maximize *total* expected return?

CMBS investors should foreclose. In the foreclosure case, the expected loss is
$150M, of which CMBS investors bear $50M (and B-piece investors bear $100M).

In the restructuring case, the expected loss is
$(30\%\times 0+70\%\times\$300=\$210)$ million, of which CMBS investors bear
$110M (again, B-piece investors bear $100M).

Thus, the loss is minimized in the foreclosure case.

### Short Question 2 Part B

> If the special servicer wants to maximize their own short-term interests, what
> should they do? Why?

To maximize their own short-term interests, the special servicer would prefer
restructuring since it extends the active servicing period and thus increases
the servicer's compensation. A foreclosure would be relatively quick, earning
the servicer less overall.

### Short Question 2 Part C

> Thinking about the longer run, are there any reasons why the special servicer
> might not want to undertake the actions you suggest in Part B above?

In the long run, the special servicer may face reputational damage from a
history of pursuing short-term gains at the cost of investors' interests (as
suggested in Part B). This may be a violation of a fiduciary duty with major
legal consequences.

Sometimes, the special servicer is also a B-piece investor. If that is so, the
special servicer may prefer a foreclosure to minimize B-piece losses. In our
example, this is not a factor since the B-piece investors face a total loss in
both cases.

### Short Question 2 Part D

> Why might the CMBS market feature a key role for B-piece investors, but the
> RMBS market does not?

B-piece investors feature prominently in CMBS markets because of the increased
risk of commercial mortgages relative to residential ones: Commercial pools have
larger loans, idiosyncratic (asset) risks, unique underwriting (rather than
standardized), and higher default risk.

For commercial mortgages, securitizers need investors with a higher risk
appetite to absorb these risks in order to make the deal marketable to the
investors of the more stable tranches. As a result, they give up some control to
B-piece investors. For residential mortgages, defaults are rarer so the role of
B-piece investors is muted.

## Short Question 3

> Consider a suburban mall that generates total lease income of $40M per year.
> Operating expenses of running the mall are $7M per year. The mall is financed
> by an interest-only commercial mortgage with an interest rate of 4% per annum.

### Short Question 3 Part A

> How would you go about assessing what an appropriate cap rate would be for
> valuing this property?

We can estimate cap rates by observing those of other suburban malls with
similar tenants, size, location and geography, and risk factors. Then, we can
adjust these comparables to account for our property's relative characteristics,
such as risk, location strength, and lease features.

We can use a regression, or other statistical model, to help estimate.

### Short Question 3 Part B

> Assume that an appropriate market cap rate for this type of property is 5%.
> What is your valuation of this property?

The value of the property is its net operating income ($\$40.00-\$7.00=\$33.00$
million), divided by its cap rate ($5\%$).

Thus, the value of the property is  $\$660.00$ million.

### Short Question 3 Part C

> Assume the mortgage has a loan-to-value (LTV) of 80%. What is the debt service
> coverage ratio (DSCR) on the mortgage?

If the loan has an LTV of $80\%$, then the loan amount is
$80\%\times \$660.00=\$528.00$ million.

The annual debt service is $4\%\times\$528.00=\$21.12$ million, since this is an
interest-only mortgage.

The debt service coverage ratio is the ratio of net operating income to debt
service, or $\frac{\$33.00}{\$21.12}=1.5625.$

### Short Question 3 Part D

> Would the DSCR be higher or lower if this was an amortizing mortgage instead
> of an interest-only mortgage? Why?

If this were an amortizing mortgage instead of an interest-only mortgage, the
DSCR would be lower. For an amortizing mortgage, the debt service would include
both interest and principal repayments, so it would be higher. Holding net
operating income constant, the DSCR would be lower.

### Short Question 3 Part E

> The DSCR is commonly used as an underwriting criterion for commercial real
> estate lending. Briefly explain how it is used, and why it is a useful
> statistic for assessing credit risk for commercial mortgages. Also give an
> example of a situation in which it might give a misleading picture of the
> credit risk embedded in the commercial mortgage.

The debt service coverage ratio measures "how many times" a property can meet
its debt obligations using its net operating income. Since it measures the
property's ability to generate enough income to pay its debts, it is a useful
statistic for assessing credit risk in commercial mortgages.

If a property's DSCR is less than 1, it is not generating enough income to meet
its obligations. With DSCR equal to 1, a property is breaking even. A higher
DSCR implies a margin of safety, as income can fall substantially without
resulting in delinquency. A falling DSCR can be a warning of stress.

DSCR may be a misleading measure if operating income is volatile: for example,
if leases are short-term, net operating income is unsustainable, or rents change
substantially.

## Short Question 4

We will reference
"[Carl Icahn Bet on the ‘Big Short 2.0.’ Now He Says the Game Was Rigged](https://www.wsj.com/finance/investing/carl-icahn-bet-on-the-big-short-2-0-now-he-says-the-game-was-rigged-1ce090aa)"
by Ben Foldy, published in the *Wall Street Journal*; "[The $2 Billion Mall Rats](https://www.esquire.com/news-politics/a34785141/shopping-mall-short-hedge-fund-covid-19/)" by Ian Frisch, published in
*Esquire*; and
"[Revisiting the CMBX 6 'Big Short' – Retail Renaissance or False Start?](https://www.trepp.com/trepptalk/checking-in-on-cmbx-6-retail-renaissance-or-false-start)"
by Manus Clancy writing for Trepp.

> Why might the value of commercial real estate (CRE) or CMBS be falling?

The expansion of e-commerce and subsequent collapse of anchor retailers like
Toys 'R' Us and Sears meant that malls were oversized compared to their sales,
especially in second-tier markets. Eric Yip of Alder Capital Management argued
that mall debt was a "toxic cocktail," since the risky mortgages were backed by
properties that were "highly likely to become ‘dead malls.’" If that happened,
tenants would not be able to pay, landlords would default, and lenders would
find their collateral impaired.

> Explain what is happening in financing markets and why this might have an
> impact on funds that invest in CRE and CMBS? As an investor, what could you do
> to take a bearish position on retail commercial real estate?

Around 2017, Eric Yip (and other investors, including his former employer Carl
Icahn of Icahn Enterprises) undertook aggressive short positions on commercial
real estate debt via credit default swaps (CDS) on the CMBX commercial mortgage
indices. These insurance products allow investors to take bearish positions on
retail commercial real estate.

Unfortunately for Yin, the CMBS values did not decline as quickly as
anticipated. In fact, in the short term, they rose: Two mutual funds propped up
the price by disclosing their large long position and accepting the other side
of Yin's CDS trade.

As a result, funds that invested in CRE and CMBS did not experience the steep
losses that Yip and the short investors anticipated. In the end, the shorts cut
their losses, costing Yip his hedge fund. Had they held until 2020, they might
have seen major gains instead.

**Conclusion:** CRE and CMBS markets can be manipulated by large investors and
their reputations. It's difficult to take an extreme position, even when you are
correct, since there are too many confounding factors.

## Problem 1: Commercial mortgages and defeasance

> It is 2019, and you work in finance for a large international media company.
> Your firm took out a $500M amortizing fixed-rate commercial mortgage on your
> U.S. corporate headquarters two years ago. The coupon rate on the mortgage is
> 5%, and the loan initially had a 25-year amortization period, and a 10-year
> balloon payment. (Note: Since two years have passed, this balloon payment will
> now occur in eight years' time). Mortgage payments are monthly.

### Problem 1 Part A

> How likely is it that this loan was financed through the CMBS market? Explain.
> How would this loan be financed otherwise?

It is likely that this loan was financed through the CMBS market, since CMBS is
common for large, high-value commercial properties like corporate headquarters.
Since the loan amount was $500M, it was large enough to be financed through a
CMBS conduit or even a SASB deal. Also, a fixed-rate amortizing mortgage with
balloon payment is a typical structure for CMBS.

Alternatively, the loan could have been financed through syndicated loans or
institutional lenders.

### Problem 1 Part B

> What if this mortgage had been originated eight years ago instead – would your
> answer to Part A be different?

If this mortgage had been originated earlier, it would be less likely for the
loan to have been financed through the CMBS market, since during and after the
financial crisis of 2008, CMBS securitization declined significantly. Later,
CMBS markets recovered but had much stricter lending standards and rtansaction
activities were still low. During this period, it would be more likely for the
loan to have been financed through traditional banks and institutional lenders.

### Problem 1 Part C

> Calculate the monthly payment on this mortgage. Also calculate the current
> face value on this mortgage.  

$$C=\text{pmt}\left(r=\frac{5\%}{12},n=25\times 12,V_0=\$500000000.00\right)=-\$2922950.21.$$

The monthly payment is $2,922,950.21.

$$V_{24}=\text{fv}\left(r=\frac{5\%}{12},n=2\times 12,C=-\$2922950.21,V_0=\$500000000.00\right)=-\$478853476.10.$$

The face value of the mortgage is $478,853,476.10.

> After a boozy lunch with some Wall Street mortgage bankers, your boss tells
> you that he has heard financing is easily available now, and that it would be
> possible to obtain new fixed-rate commercial mortgage financing on the
> corporate headquarters at a lower interest rate of 4%. He tells you to look
> into the costs and benefits of refinancing the existing mortgage to take
> advantage of lower rates.  
>
> Looking at the mortgage contract, you notice that in order to refinance, you
> will be required to defease the existing mortgage. Assume that current
> long-term Treasury yields are 3%, and the yield curve is flat. Also assume
> that if you refinance now, the new mortgage would have the same initial
> contract terms as the loan you currently have (i.e. 25 year term, 10 year
> balloon payment).

### Problem 1 Part D

> Assume you refinance the mortgage in a way that involves a zero up-front net
> cash payment. In other words, when you refinance, you borrow exactly as much
> as it costs to defease the old mortgage. Under this approach, what would your
> new monthly payments be? Explain intuitively the reason why your monthly
> payment went up or down relative to your calculation in Part C.

For simplicity, ignore the difference in payment schedule for Treasury bonds.
That is, assume that there is a 3% Treasury bond with monthly cash flows.

To replicate the payments using a Treasury bond, we first calculate the amount
of the bullet payment in eight years (ten years from loan initiation):

$$V_{120}=\text{fv}\left(r=\frac{5\%}{12},n=10\times 12,C=-\$2922950.21,V_0=\$500000000.00\right)=\$369622377.91.$$

We will need to supply a risk-free asset (Treasury bond) maturing in eight years
with a terminal cash flow of $369,622,377.91 and regular cash flows of
$2,922,950.21 per month.

$$V_{24}'=\text{pv}\left(r=\frac{3\%}{12},n=8\times 12,C=-\$2922950.21,V_{120}'=\$369622377.91\right)=-\$540037315.02.$$

The total amount to borrow is $540,037,315.02.

Thus, the mortgage payment is given by:

$$\text{pmt}\left(r=\frac{4\%}{12},n=25\times 12,V_0''=\$540037315.02\right)=-\$2850515.90.$$

The mortgage payment is $2,850,515.90 per month. This is lower than the existing
monthly payment because the 4% rate is low enough to offset the cost of
defeasance. Since the Treasury asset is more expensive than the mortgage,
defesance comes with a cost. However, the 100 bp difference in the mortgage rate
makes refinancing worthwhile. If the Treasury rate were lower than 3 percent or
the mortgage rate were higher than 4 percent, this might not have been the case.

### Problem 1 Part E

> Given this answer from Part D, do you recommend defeasing the loan to take
> advantage of the lower market rates, and why?

Given the lower payment in Part D, it is worthwhile to defease and refinance the
mortgage. The benefits of refinancing offset the costs of defeasing in this
case.
