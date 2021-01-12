# ib-test

You have invested in a 3x leveraged ETF or Factor Certificate on underlying XYZ. The market initially drops but you continue to believe XYZ will recover, and it does. However due to the daily leverage feature, your investment will still show a loss:
  	Underlying X 	3x Daily Leverage
  	Value 	% Change 	Value 	% Change
Initial 	100 	  	100 	 
Day 1 	95 	-5.00% 	85 	-15.00%
Day 2 	94 	-1.05% 	82.32 	-3.16%
Day 3 	95 	1.06% 	84.94 	3.19%
Day 4 	98 	3.16% 	92.99 	9.47%
Day 5 	100 	2.04% 	98.68 	6.12%
Total Performance

At the time they're issued, bonus certificates normally have a term to maturity of two to four years. You will receive a specified cash pay-out ("bonus level" or "Strike") if at maturity the price of the underlying is below or at the strike, as long as the underlying instrument has not touched or fallen below an established price level ("safety threshold" or "barrier") during the term of the certificate.

Unless the certificate has a cap, you continue to participate in the price gains if the underlying instrument rises above the bonus level. In this case you either receive the corresponding number of shares or a cash settlement reflecting the value of the underlying instrument on the maturity date.

However, if the barrier is breached, you will no longer be entitled to the bonus payment. The value of the certificate then corresponds to the value of the underlying (times the ratio). In other words, once the barrier has been touched the certificate effectively converts to an index certificate.
EXAMPLE - Turbo Certificate

Knock-out warrants (turbos), like vanilla warrants, derive their value from the difference between the price of the underlying and the strike. They differ significantly however from vanilla warrants in many important respects:

    They can expire worthless (knock-out) prematurely if the price of the underlying instrument touches or falls below (in the case of knock-out calls) or exceeds (in the case of knock-out puts) a predetermined barrier-level.
    Changes in implied volatility have little or no impact on knock-out products, therefore their pricing is easier for investors to comprehend than that of warrants.
    They have little time value (because of the presence of the knock-out barrier time value is limited to financing and "issuer premium"), and therefore have a higher degree of leverage than a warrant with the same strike. This is because the limited time value makes the instrument "cheaper".


strike=36
index=40
price=4.2
leverage=9.5

Intrinsic value = (index value – strike) x ratio
Leverage = Index Value x Ratio / Instrument Price

4, 0.20


9.5=40*ratio/4.2
ratio=(leverag/index valeu_)*price
ratio=(9.5/40)*4.2=1
intirn=(40-36)*1=4


Leverage = 45 * 1 / (4.2+5)
4.9


Leverage = 45 * 1 / (4.2-3)
30




