* given 2 addresses, we need to be able to make multisig addresses.
  * mk_multisig_script   : (pubkeys, k, n) -> k-of-n multisig script from pubkeys
  * scriptaddr           : (script) -> P2SH address

* We need to be able to make a tx with many inputs, to be signed by 2 different people, with the 2 of 2 as an output, and 2 change outputs.
  * mktx(ins, outs)


* We need the ability to make a tx that spends from a 2 of 2 to 3 seperate people.
  * mktx                 : (inputs, outputs) -> tx

* We need the ability to take 2 partially signed transactions, or 2 signatures, and make it into one transaction that is completely signed.
  * deserialize          : (hex or bin transaction) -> JSON tx
  * apply_multisignatures: (tx, i, script, sigs) -> tx with index i signed with sigs

* We need to check if the money in a 2 of 2 address on the blockchain has moved. We need to be able to tell how much of the money went to each of two users.
  * history              : (address1, address2, etc) -> outputs to those addresses

* We need the ability to count up all the coins every sent to an address.
  * history              : (address1, address2, etc) -> outputs to those addresses

* given an address, we need to know it's balance.
  * unspent              : (address1, address2, etc) -> unspent outputs to those addresses
