# How to Determine Value
It turns out there are a lot of different ways to evaluate how well an investment does.  To be completely honest, I find many of them to be fairly confusing, so I’m going to try to clarify all of these for myself (and hopefully others).  In order to do that, I’ll try to use the same amount all of the time to see how they are different.  If you're one of those people who feels more comfortable playing with the numbers in Excel, [I have created a workbook](References/intro-to-investing.xlsx) that has all of these calculations as well, so that you can go be a dirty number fiddler.

## Rate of Return (a.k.a. Return)

The simplest calculation.  Given how much money you invested, how much money did you make?  This is the same as calculating any other percentage

(Actual – Standard)/(Standard) or in investment terms (Current Value – Original Value)/(Original Value)

E.g.  $100 invested for 5 years, and at the end it was worth $110.  (110 – 100) / 100 = .1 or 10%

## Annualized Return (a.k.a. Compounded Annual Growth Rate (CAGR))
Knowing your total return is useful, but often you want to be able see how you did per year.  So, the obvious answer is to simply divide it by the number of years.  

E.g.  $100 invested for 5 years, and at the end it was worth $110.  Rate of Return is 10% (from above).  10% / 5 years = 2%.

Regrettably this is wrong, and the reason is that it fails to take into account the compounding of money.   I’m going to break it down into pieces just to make it easier to follow.

First, calculate how much money you have, as a percentage, of your original investment.

$110 / $100 = 1.1

Then, add in the compounding part

1.1 ^ ( 1 / 5  Years) = 1.019

Because this includes your original investment, you need to remove your initial money (or 100% which is also 1).

1.019 – 1 = .019 which is 1.9%

So, when calculated with compounding your rate of return is actually slightly less than the simple number.

## Time Value of Money (TVM)
Before we can dig into some of the more complicated calculations, there are a couple of critical things to understand.  TVM is one of those.  TVM simply states that money that you have right now, is more valuable than money you might have in the future. 

If you have $100 right now, you could invest it and get 10%, and in one year it would be worth $110.  But if you get that $100 in one year, then it’s still only $100, which means it is not as valuable, because $110 is greater than $100, even for very large values of $100.

*finish this*

## Net Present Value (NPV)

TBD

## Internal Rate of Return (IRR)

TBD

## Capitalization Rates (Cap Rates)

TBD
