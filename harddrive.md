* to store open trades, waiting for a partner.
  * amount to trade
  * price
  * safety deposit size
  * other safety deposit size
  * details about non-cryptocurrency payment
  * email address for first person.
  * trade id (don't reuse ids in the same 24 hour period.)

* to store signatures for a part-ways completed trade, step 1
  * One signature moving funds into multi-sig.
  * store second email address.

* to store signatures for a part-ways completed trade, step 2
  * Publishes tx that loads money into multi-sig.
  * Gives email addresses to each participant.

* to store signatures for a part-ways completed trade, step 3
  * One signature for unlocking funds from multi-sig.

* to store signatures for a part-ways completed trade, step 4
  * Has both unlocking signatures. Either records it as a success, or a weird situation.

* to store data that we asked a user to sign to prove control of an address.