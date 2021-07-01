### MEASURING LUCKINESS 
In order to measure the "luckiness" of a transaction, I first had to come up with mathematical definitions of luckiness. I eventually settled on two different ones; one to measure the timeliness of a purchase and another to measure the timeliness of a sale.

For purchases, I decided that I would look at the change in stock price 3 months after the declaration date and normalize by dividing over the initial price. I also wanted to take into account how well the stock's performance compares to VTSAX, Vanguard's Total Stock Market Fund and the largest component of my portfolio.

The resulting equation for purchases looks like this:

The equation measures the increase in stock price and checks whether or not I would have been better off putting Intuitively, if both VTSAX and the stock price increase AND the stock price increases faster than the price of VTSAX, then the transaction is considered lucky. However, if the stock price increases but VTSAX increases faster, then the money would have been better off being placed in VTSAX. 
