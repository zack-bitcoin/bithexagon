* creating account
  * solution to a captcha.
  * email address
  * pubkey
  * list of bitcoin addresses
  * signature

* update account info
  * new email address
  * new list of bitcoin addresses
  * signature

* update password
  * bitcoin address you control 
  * data the server provides
  * signature using the private key for the address.

* join an active trade
  * signature

* cancel unstarted trade
  * trade id
  * signature

* start trade 
  * trade id
  * signatures for addresses this trader controls.
  * signature

* cancel started trade (can only be canceled if you both cancel)
  * trade id
  * signature for bitcoin address used in multisig.

* finish trade (can only be finished if you both finish)
  * trade id
  * signature for bitcoin address used in multisig.
  * signature

* list open trades 

* list my active trades (this is where you see your partner's email or phone number when it is time)

* user lookup

* propose new trade
  * buy/sell bitcoin
  * amount in bitcoins
  * type of fiat
  * amount in fiat
  * details of non-blockchain money transfer.
  * signature

