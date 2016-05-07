Bob wants to sell Bitcoin. Alice wants to buy. Charlie is running the server used to match Bob to Alice.

Bob uses a browser to communicate to Charlie's server.
Bob pays a fee to get his trade offer listed on the server. Bob gives a list of addresses that he controls, so Charlie can make transactions for Bob to sign. Bob gives a minimum ratio between the amount of coins he is selling, and the safety deposit his partner will have to put up. Bob must have enough coins to cover the sale, and another safety deposit.

Alice uses a browser to look at Charlie's server, and see the trade that Bob offers. She makes a small payment to accept the trade. She has to give a list of addresses that she controls, along with an email address, so that Charlie can make transactions for her to sign. She has to have enough coins to cover the safety deposit. Since she made a payment, we can afford to store her lists of addresses.

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