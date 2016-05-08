Bob wants to sell Bitcoin. Alice wants to buy. Charlie is running the server used to match Bob to Alice.

Bob and Alice use a browsers to communicate to Charlie's server.
Bob registers for the server, which includes paying a fee in bitcoin, and giving a list of addresses that Bob controls. Depending how much a fee he paid, he gets non-refundable credits. You spend credits to do most things on the site. You also give an email address or other type of contact information that will be given to your trading partners.
Alice registers too.

Bob pays a fee in credits to get his trade offer listed on the server. Bob decides a minimum ratio between the amount of coins he is selling, and the safety deposit his partner will have to put up, and the safety deposit he puts up. Bob must have enough coins to cover the sale, and his safety deposit.

Alice uses a browser to look at Charlie's server, and see the trade that Bob offers. She makes a small in credits to accept the trade. She has to have enough coins to cover the safety deposit.

Charlie possibly takes the trade offer off the server, if we reached the limit Bob wanted to trade.

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