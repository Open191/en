# Withdraw ELFT

The withdraw system works on an individual basis, each person will have a different fee depending on how long he/she has been waiting between withdrawals.

We know that when panic situations are generated, people can be influenced to sell. Our way to counteract these situations is as follows:

The Withdraw rate will start from 75%. Every day it will be reduced by 5% until it reaches the minimum, 5%. 60% of the withdraw rate will go to burn token, which will result in a significant increase in value. So when a person panic sells, something that should hurt the market, he will be benefiting the ELFT, since if the rate is high, he will be contributing to burn a lot of tokens.

Every day is reduced by 5% which would be the withdraw rate:

| Date of waiting (Day) | Rate |
| --------------------- | ---- |
| 0                     | 75%  |
| 1                     | 70%  |
| 2                     | 65%  |
| 3                     | 60%  |
| 4                     | 55%  |
| 5                     | 50%  |
| 6                     | 45%  |
| 7                     | 40%  |
| 8                     | 35%  |
| 9                     | 30%  |
| 10                    | 25%  |
| 11                    | 20%  |
| 12                    | 15%  |
| 13                    | 10%  |
| 14                    | 5%   |

Once we remove it, the day counter will start again.

Practical examples:

* Case 1:Withdraw 100 ELFT. If you choose to arrive in 3 days, the withdrawal fee will be 60%. After the 5th day, 40 ELFT will be received. Pay 60 ELFT (100\*60%) as a handling fee, of which 36 ELFT (5\*60%) will be used for destruction.
* Case 2:Withdraw 100 ELFT. If you choose to arrive within 14 days, the withdrawal fee will be at least 5%. After the 14th day, 95 ELFT will be received. Pay 5 ELFT(100\*5%) as a handling fee, of which 3 ELFT tokens (5\*60%) will be used for destruction.
