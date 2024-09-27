---
title: Blending the streams
weight: 6
type: docs
slug: blending_the_streams
---

The three streams in this model can all happen simultaneously, although a mature collective will eventually only use the CS stream and a lot of this complexity can go away. The primary implication of blending the stream is the way that financial contributions are calculated, both in terms of the amount, the implications for making them, and the options for changing or reducing them.

Essentially this works by determining a proportion of the scheme being managed under each stream, and this is updated regularly (generally monthly). Simply put, that means that if 10% of the communities’ asset value is mortgaged, then 10% of the calculation for everyone’s regular financial contribution is calculated using the formulas for the Bank Mortgage stream.

This is, however, one necessary case of a gate that must be passed before moving on. That’s because if there’s a mortgage, it really must be paid or there are dire consequences, and that may not leave money over for other stream calculations if contributions are to remain affordable. That is discussed under “stream gates”.

## Stream asset ratio

At any point in time, the housing collective is able to calculate a ratio of the economic value of its assets and which party’s funds have been used to secure them.


|Bank Mortgage Stream|Transitional Equity Stream|Collective Stewardship Stream|
|--------------------|--------------------------|----------------------------|
|Total of bank loans|Total of Transitional Equity Balances|Total asset value minus the totals from the other two streams|


These totals are used to give a ratio, expressed as percentages. For example, if the collective has the following properties and mortgages:

| |Valuation|Mortgage|
|--|--------|--------|
|Property 1|$1,000,000|$400,000|
|Property 2|$2,000,000|$1,400,000|
|Property 3|$1,000,000|$800,000|
|TOTAL|$4,000,000|$2,600,000|

And additionally it has $1,000,000 of transitional equity balances “owed” to individuals within the collective, then there is still $400,000 unencumbered. This gives the following inputs to the formula:

|Category|Input|
|------|----------|
|Total of Bank loans|$2,600,000|
|Total of Transitional Equity|$1,000,000|
|Total asset value|$4,000,000|

And the following totals and ratios (expressed as percentages):

|BM Stream|TE Stream|CS Stream|
|---------|---------|---------|
|$2,600,000|$1,000,000|$400,000|
|65%|25%|10%|

## Stream gates
There is a “gate” between streams in the model, which is essentially that percentage for the BM stream cannot drop below that needed to make the mortgage payments. The formula for regular financial contributions under the BM stream is essentially just “apportion the mortgage amongst people”, so theoretically any percentage ratio for the BM stream works, but the amount for regular financial contributions could become too large to be affordable.

To avoid that unaffordability, streams subsequent to the BM stream are only used in the calculation of regular financial contributions once regular financial contribution under the BM stream drops below the BM stream affordability metric.

## Financial contributions by ratio
Hopefully it’s clear from the above that each month, each individual will make a financial contribution made up of three parts according to the current ratio. For example, presuming the BM stream gate is reached (see above), that contribution might look as follows :

||BM Stream|TE Stream|CS Stream|Total|
|--|-------|---------|---------|-----|
|Stream formula result|$2,000|$1,500|$750|N/A|
|Stream ratio|65%|25%|10%|100%|
|Ratio based component|$1,300|$375|$75|$1,750|

*Numbers are roughly based on 40%, 30% and 15% of a $60,000 gross income*

Hopefully this shows that the more the model moves towards the CS stream, the cheaper it will be. For example, imagine about half of those percentages have shifted to the right.

||BM Stream|TE Stream|CS Stream|Total|
|--|-------|---------|---------|-----|
|Stream formula result|$2,000|$1,500|$750|N/A|
|Stream ratio|30%|30%|40%|100%|
|Ratio based component|$600|$450|$300|$1,350|

And finally, imagine that the mortgages are paid off, and all the Transitional Equity bought out, then of course the total contribution would be the CS stream amount, $750 on a $60,000 salary, or maybe zero in retirement. 


