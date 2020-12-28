# NewYorkCoin [NYCoin, NYC]
==========================

![NewYorkCoin](https://nycoin.community/images/logo-inverse-210x76.png)



## What is NewYorkCoin?
NewYorkCoin is a cryptocurrency like Bitcoin, although it does not use SHA256 as its proof of work (POW). Taking development cues from Dogecoin and Litecoin, NewYorkCoin is built to be cryptocurrency solution for inexpensive global value transmission

https://nycoin.community/


Development Bounties:

* Bounty 1. Update NYC source code to introduce: SegWit, support for Atomic Swaps, and support for Lightning Network - 200m NYC ( bounty submission accepted - https://github.com/NewYorkCoin-NYC/nycoin-2.0/commit/61b54d4a8ea62d6c1a4372d35e9904d024f7f724 - funds dispersal is in progress)
* Bounty 2. Develop proprietary merchant integration solution - 250m NYC
* Bounty 3. Bug Bounty: 75m NYC

Requirements:

Bounty 1. Upgrade the NYC codebase to include the Segregated Witness Protocol, support for Atomic Swaps, as well as the Lightning Network Protocol. Code must be reviewed by the NewYorkCoin development team prior to payment for completion of the bounty.

Bounty 2. Develop a working Android/iOS mobile NYC wallet, with inventory management and point of sale capabilities, similar to Square. App must be reviewed by the NewYorkCoin development team prior to payment for completion of the bounty.

Bounty 3. Find and report any bug or exploit that you can find in the NewYorkCoin code to contact@nycoin.community. Bug/exploit must be verified by the NewYorkCoin development team prior to payment for completion of the bounty.

Please direct all correspondence in regards to these development bounties to contact@nycoin.community or join our discord https://discord.gg/DhgxUqJ. Thank you!


## License
NewYorkCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Development is ongoing, and the development team, as well as other volunteers, can freely work in their own github branch and submit pull requests when features or bug fixes are ready.

## Alerts
The crypto community is filled with scams and individuals seeking to take advantage - sadly the NewYorkCoin project is not immune and it has come to our attention that a copy cat website is being used to spread disinformation and drive traffic to Yobit - an exchange that is known to be trading NewYorkCoin with insufficient reserves due to a 51% attack and has locked withdrawals since the attack (with the exception of a short ~1 week period).

The fraudulent site is nycoin.net and appears to be associated with NewYorkCoin.net.
The fraudster also uses the twitter handle @NewYorkCoinNYC and goes by several aliases incuding nycminer, scryptenthusiast as well as hivewalletmind.

To bolster his scam the user is attacking the core dev team with easily disprovable accusations that malware was used to perform a 51% attack on NewYorkCoin while providing no evidence of how this is even possible.  At this time we know of no mechanism to use malware infected wallets to break consensus or generate sufficient hashrate to control an ASIC only PoW algorithm and there are no documented examples of this happening.  Conversely there are dozens of documented 51% attacks and all low hashrate PoW coins are vulnerable.

To combat 51% attacks the core dev team adopted merged mining(AuxPoW) which has raised the average hashrate from less than 100GH/s at the time of the attack to 1.5Th/s.  The core dev team works with multi-pools and exchanges to consistently increase hashrate and monitor large transactions to defend against double-spends.  One of the great success stories of this collaboration is the recovery of nearly 1 Billion NYC, funds that had been used to 51% attack the network. Those funds have been allocated to DEV bounties.

Unrelated to 51% attacks are the rather common malware injection attacks targeting crypto-currency related repositories on github.  The core dev team has taken all necessary steps to lock down the github repo by enforcing 2-factor authentication, limiting the number of team members with access to the organization and using our own custom discord bot to monitor https://api.github.com/repos/NewYorkCoin-NYC/nycoin/releases for unauthorized changes since the tools provided by GitHub were, at least at the time, insufficient.

For a better understanding of the 51% attack see https://medium.com/@newyorkcoin/timeline-analysis-and-response-to-recent-51-attack-941da50d625c

As always the best source of fact checked information is https://nycoin.community/ where you will find links to all trusted social media.

