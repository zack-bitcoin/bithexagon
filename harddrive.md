* A database for remembering who is adding credits to their account. Once their tx has 2 confirmations, we give them the credits.

* A database for remembering trades that are about to be completed onto the blockchain. Once they are 2 confirmations deep, add them to the user's reputation.

* to store open trades.

* to store signatures for a part-ways completed trade, and remember what step we are on.

* to store information for each account. If the account runs out of credits, it gets deleted. Every day you lose credits, even if you don't do anything.
  * lists of addresses
  * email
  * balance in credits
  * total amount of bitcoin ever transformed to credits
  * history of past trades.


* to store solutions to captchas. Each captcha has an ID. We store the solution by ID. Once the captcha is older than 10 minutes or so, we delete it from the database.