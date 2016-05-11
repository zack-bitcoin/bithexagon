Bob wants to sell Bitcoin. Alice wants to buy. Charlie is running the server used to match Bob to Alice.

Alice and Bob used to have their money split into many many addresses. In preperation for this trade, they moved enough money into a single address as they need.

Bob and Alice use a browsers to communicate to Charlie's server.

Bob pays a fee in bitcoin to get his trade offer listed on the server. Bob decides a minimum ratio between the amount of coins he is selling, and the safety deposit his partner will have to put up, and the safety deposit he puts up. Bob must have enough coins to cover the sale, and his safety deposit.

Alice uses a browser to look at Charlie's server, and see the trade that Bob offers. She accepts.

Charlie possibly takes the trade offer off the server, if we reached the limit Bob wanted to trade, otherwise it is split into 2 trades, one is still an open offer.

Charlie makes a 2 of 2 multisig address using Alice and Bob's addresses. He makes a transaction that spends some of Alice's coins, the safety deposit, and it spends some of Bob's coins, the ones he wants to sell and another safety deposit. All this money is put into the 2 of 2 multisig.

Alice and Bob each sign the tx, and give their signatures to Charlie's website. Charlie broadcasts this transaction. 

Then Charlie gives Bob Alice's email, and gives Alice Bob's email so they can communicate for the next steps.
We didn't trade emails until their money is locked in. That way you don't get as much spam.
Charlie makes a transaction that gives Alice her safety deposit back, and gives Bob his safety deposit back, and gives the coins Bob wanted to sell to Alice to Alice.

Alice uses a non-cryptocurrency method to pay Bob.

Alice and Bob sign the transaction they got from Charlie, and give their signatures to the server or broadcast the tx. It is important that Bob does not sign until he gets paid by Alice. This also returns the safety deposits to the correct owners.

Charlie notices that the money moved in the expected way, and he records a successful trade into Alice and Bob's reputation.
If the money moved in an unexpected way, he records it as a weird trade and includes details in both their reputations.
If the trade never finishes, then eventually record it as lost funds.