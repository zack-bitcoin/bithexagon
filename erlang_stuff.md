* to create a new account, we need to remember userid/email combos we emailed after they solved captchas. When they click a link, it provides a code. We need a database containing acceptable codes from people who actually solved captchas. The database contains the userid/email associated to each code. There should be a 2 hour time limit for each item in this database.

* A database for remembering who is adding credits to their account. Once their tx has 2 confirmations, we give them the credits.

* A database for remembering trades that are about to be completed onto the blockchain. Once they are 2 confirmations deep, add them to the user's reputation.

* to store open trades.

* to store information for each account
  * lists of addresses
  * email
  * balance in credits
  * total amount of bitcoin ever transformed to credits
  * history of past trades.

* to store solutions to captchas. Each captcha has an ID. We store the solution by ID.