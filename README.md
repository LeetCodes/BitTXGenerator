# BitTXGenerator

I'm proud to announce the release of BitTXGenerator 1.2.1

An open source program that can generate fake Bitcoin transactions and broadcast them to the Bitcoin network.

Video Demonstration: http://sendvid.com/6pgywmr9

Windows 32/64 Binary: https://mega.nz/#!2J9njYLI!PCHpyS4js8CwpARC8dEK7Ky9-ft7a5Tf5zz07vNKiVQ


Updates (10/06/2016):

Fixed several connection error bugs.

Fixed a bug where sometimes it wouldn't successfully validate the transaction while broadcasting.

Added the option to use Combined output overflow in the generated TX.

For those of you that do not know about the program, BitTXGenerator generates false Bitcoin transactions using a valid Sending and Receiving address and a satoshi amount (one satoshi = 0.00000001 BTC).

The transaction will validate for one block (about 10 minutes) and then will get a "Negative Confirmation" a short time after the next block.

The transaction will appear on the blockchain and all the Bitcoin clients as a normal Bitcoin transaction until it gets a negative confirmation.

I'm open to any input/suggestions for the next version. Also if you're having any trouble using the program, please contact me.

Disclaimer:
By using this program, you agree to not create any malicious bitcoin transactions, use this program to spam/disrupt Bitcoin, or for any type of illegal use.
