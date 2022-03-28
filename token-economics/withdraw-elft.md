# ELFT Withdraw

The token withdrawal system operates on an account basis, and each account will be charged a different fee, depending on the latency time selected by the player.

We know that when there is a panic situation, people may be affected to become eager. Our approach to these situations is as follows.

The withdrawal rate will start at 75%. Every day it will decrease by 5% until it reaches the minimum value of 5%.

60% of the withdrawal rate will be used to destroy the tokens, which will result in a significant increase in value. Thus, when a person sells something that should hurt the market in panic, he will benefit from ELFT because if the rate is high, he will help destroy a large number of tokens.

For each additional unit of latency time, the withdrawal rate is reduced by 5%, which will be the rate for withdrawing tokens:

| Latency time (day) | Withdrawal rate |
| ------------------ | --------------- |
| 0                  | 75%             |
| 1                  | 70%             |
| 2                  | 65%             |
| 3                  | 60%             |
| 4                  | 55%             |
| 5                  | 50%             |
| 6                  | 45%             |
| 7                  | 40%             |
| 8                  | 35%             |
| 9                  | 30%             |
| 10                 | 25%             |
| 11                 | 20%             |
| 12                 | 15%             |
| 13                 | 10%             |
| 14                 | 5%              |

After an withdrawal is completed, the token withdrawal counter will restart.

Real examples:

* Case 1: For withdrawal of 100 ELFT, the withdrawal rate is 60% if the tokens are withdrawn on the 3rd day. Then 40 ELFT will be credited. 60 ELFT (100\*60%) will be paid as service charge, in which 36 ELFT (60\*60%) will be used for destruction.
* Case 2: For withdrawal of 100 ELFT, the withdrawal rate is a **minimum of 5%** if the tokens are withdrawn on the 14th day. Then 95 ELFT will be credited. 5 ELFT (100\*5%) will be paid as service charge, in which 3 ELFT (5\*60%) will be used for destruction.

The above token withdrawal system is applicable to all sessions of in-game pledge training, PVE, PVP, etc.
