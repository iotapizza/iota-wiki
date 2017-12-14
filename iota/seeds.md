<!-- TITLE: Seeds -->
<!-- SUBTITLE: Seeds on the IOTA Tangle -->

# Seeds
The seed is used to generate the successive private keys for each address in the wallet.
It is impossible to ever determine the seed from these private keys, because the hashing involved is an irreversible action.

From each private key a public key is derived, again by hashing. That public key is what we call the address. From the address it is impossible to determine the corresponding private key, because the hashing involved is an irreversible action.

Sending funds *into* an address is always allowed. You don't have to sign to receive into an address.
That's why multiple sends into an address are no problem. The nodes will simply add up all transfers into that address balance.

However, when you want to send funds *out* of an address you need to prove that you are the owner of that address.
This is done by signing the transaction with your private key.  The nodes will check if your signature is correct, and only then allow the funds to be transferred. Due to the one-time signature nature of IOTA's signing method when you sign a random 50% of your private key gets exposed.
That in itself is no problem. The funds are transferred, normally quickly, and end up in an address that has had no spends. The remaining funds from the address that now has a partially compromised key are moved in the same transaction to a fresh, unspent address. So far so good.
The problems arise when you receive again in that now spent address. To be able to move those funds you will have to sign *again* which means you compromise another random 50% of your private key. Depending on your luck a small or large part of overlap with the previous reveal may occur. On average you end up with a 75% exposed private key. But randomness being what it is you could end up even with 90% exposed.
Any way, your private key now has become brute force-able and the bandits out there are going to try to crack it before your second transaction confirms.