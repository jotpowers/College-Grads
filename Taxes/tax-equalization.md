# Tax Equalization

# Introduction

I was part of a program where we were lucky enough to be able to work internationally for six months.  However, one of the challenges with that is the recognition that you're now dealing with the complications of international taxes, or taxes at a location that are different from your home location.  Relocation is supposed to be tax neutral.  You should neither owe or be owed more due to your relocation.  In my experience, the tax accountants ability to be able to explain how this is calculated, can be described as inadequate at best.  At worst it's gross incompetence.  If you're lucky they'll explain how A - B = C.

*Note:*  There is also a basic [spreadsheet available](References/tax-equal.xlsx).
 
# United States
 
## Base assumptions

In order for this to work we have to come up with some basic make-believe numbers that we'll work with.

### W-2
The W-2 will have the following numbers you care about:
* Salary: $100,000
* Relocation Taxable Gross-Up: $15,000
* Relo Gross Up Offset: $10,000

### Tax rates

We'll assume you live in the U.S. with a tax rate of 20%.  You're also domiciled in the state of Taxlandia with a tax rate of 5%.

## Maths
We're going to assume that you paid $0 in taxes.  Primarily, because what you paid doesn't really matter, and it just adds one level of maths.  What you care about is what you have to pay or are owed.

## Actual W-2

W-2|$100,000
---|---
20%|$20,000
5%|$5,000
Total liability|$25,000

But this includes that taxable gross-up.  If we remove it, what do we get?

## Hypothetical W-2
Your hypothetical W-2 is simply your actual W-2 minus Relocation Taxable Gross-Up.  ($100,000 - $15,000)

Hypothetical W-2|$85,000
---|---
20%|$17,000
5%|$4,250
Total liability|$21,250

## Calculations
Difference is $3,750, so that's what your company owes you in tax equalization, right?

Wrong!

You'll notice that at nowhere in here have we used the Relo Gross Up Offset.  This is the amount of money that your company actually paid you, and it's different than the Relocation Taxable Gross-Up.  That difference is the amount of money that your company paid directly to the government. 

In our case:
* Taxes paid to the government = Relocation Taxable Gross-Up - Relo Gross Up Offset 
* $5,000 = $15,000 - $10,000

That amount gets applied to the taxes owed.  So now the math is:
* Total tax liability - Hypothetical tax liability - Taxes paid to the government by your company = What you are owed/owe 
* $25,000 - $21,250 - $5,000 = -$1,250 (that you pay your company)

Congratulations, you owe your company $1,250

Obviously if the Taxes paid to the government are less than the difference between your Total tax liability and the Hypothetical tax liability, your company would pay you.  For instance if we change our numbers to:
* Relocation Taxable Gross-Up: $15,000
* Relo Gross Up Offset: $14,000

Suddenly Taxes paid to the government = $1,000
* $25,000 - $21,250 - $1,000 = $2,750 (that your company would pay you)

# United Kingdom

Most of this is specific to my experiences.  It could be that it isn't relevant for you, but I'm leaving here on the off chance a random Google search landed you here and it was useful.
 
Your accountant will have you register for self-assessment and inform HMRC that you've left the UK for tax purposes, even if you only intend to do a single rotation overseas.

They will then instruct payroll to withhold from your salary the normal amount in "hypothetical" tax contributions, and your company will settle any tax obligations you have in the UK and overseas using that amount. Any gains/losses are kept by your company, and you personally shouldn't have to do a great deal. The alternative option is that payroll withholds nothing (i.e. you get paid gross) and you later settle up whatever is required. Quite frankly this idea terrifies me, and when it started happening unexpectedly I couldn't transfer the money back fast enough. So keep an eye out for that.
Make sure you keep accurate records of your whereabouts in the some sort Travel Tracker - I recommend recording all your travel in your diary (with something like TripIt) and updating your accountant every month or so.

Pro-tips:
* Start working on this ASAP after April. Leaving it until later in the year will only cause misery.
* As you've probably never done self-assessment before, make sure you push-back on your accountant to explain anything you don't understand in the online tax planner and make them explain things over the phone in detail if necessary. The tax planner uses seemingly innocuous questions that aren't, and lots of Suspiciously Capitalised Words that probably mean something very important. None of these will have helpful descriptions. (Do you have a Home in the UK? Even though you've been told you've left the UK and are no longer Resident? Do you have a Home overseas? Does company-paid temporary accommodation count as a Home? Why is Home capitalised? Who knows!)
* Make sure you have the last 12 months worth of payslips available and P60s for the last three years.
  * *Note*:  I actually don't know what it means, but someone added it who did know, so a good idea to be aware of.
* You will need to provide detailed pension and student loan contributions, although these can be calculated from your payslips if necessary.
  * *Note*:  I actually don't know what it means, but someone added it who did know, so a good idea to be aware of.

