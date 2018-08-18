Bitcoin Extended Public Key Converter
=====================================

What is this tool?
----------------

Most Bitcoin wallets these days support [BIP32](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), 
Hierarchical Deterministic Wallets. This enables a user to keep track of a single piece of data from which a nearly 
infinite number of public/private keypairs can be generated deterministically. As Bitcoin wallets have increased in 
complexity over the years, there are now a variety of different versions of extended public keys. You can convert an 
extended public key from any version to a different version by changing the "version bytes" but this is hard to do 
if you aren't an experienced developer. This tool makes it simple for anyone to convert between different versions.

Who needs this tool?
----------------
Bitcoin wallet developers may find this tool helpful during testing, such as for switching between mainnet and testnet versions.

Bitcoin users may find this tool helpful if they are trying to import watch-only wallets into software that expects 
a specific version of extended public key with regard to the paths used for key derivation.

Standards
-------
This tool uses version bytes as described in [SLIP-0132](https://github.com/satoshilabs/slips/blob/master/slip-0132.md)

License
-------

The Bitcoin Extended Public Key Converter is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.
