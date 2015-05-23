# LFO Souce Code v3.0
LFO: the First Local Family Owned Secure, Cost-efficient, Decentralized Cryptocurrency for local communities around the globe. 
Version 3.0 May 23, 2015
Jeff Grant 
jeff@kingcountylfo.com

Preface
This intitial launch of LFO Coin Project hopes that this white paper will spark an honest, fact-based debate on the pros and cons of the two main existing systems used to provide security for peer-to-peer cryptocurrencies: proof-of-work and proof-of-stake and proof of integrity.
LFO believes that its own marketing models are more effective and natural to spread to mainstream cryptocurrency users. As such, LFO is the first peer-to- peer cryptocurrency, regardless of technology, that is secure, cost-efficient and decentralized in the long run, and continously involved in bringing in newcomers, and communities into digital currencies markets.
This LFO Project is requesting any and all members of the cryptocurrency community to make comments, suggest edits, point out potential flaws in the paper, or even add their specialty skills to the further technological development of this blockchain technology. LFO bounties will be rewarded by the LFO Code foundation for all constructive input, both positive and critical (click here for details).
Note that this paper does not discuss consensus algorithms based on trusted nodes (the systems used by Ripple and Stellar) because while that protocol has similar benefits to those of proof-of-integrity, it requires users to trust third parties and beyond that, depends on trustworthy third parties to support the network by operating nodes, which may or may not happen over time.
Also not covered in this paper is the enormous side benefit derived from not having to distribute the currency supply to proof-of-work miners to cover their operating costs. Capitalizing on this opportunity, LFO distributes the currency strategically to all the participants who increase its utility and value. Please visit LFO’s wiki  for a summary of LFO’s distribution and user adoption plans.
LFO is a decentralized peer-to-peer cryptocurrency derived from Litecoin, which itself was derived from Peercoin, and itself from open source whitepaper of Satoshi Nakamoto’s Bitcoin. 
LFO increases security relative to Peercoin and other existing proof-of-work currencies in numerous ways, including: (1) incentivizing nodes to continuously stake coins over time through substantially higher mining rewards and lower minimum stake age; (2) abandoning the use of coin age in the mining formula; (3) causing the stake modifier pa¬rameter to change over time for each stake; and (4) utilizing a client that punishes nodes that attempt to mine on multiple branches with duplicate stakes.
This paper demonstrates how LFO’s proof-of-integrity implementation addresses all commonly raised “nothing at stake” objections to generic proof-of-integrity systems. It also reviews many of the flaws of proof-of-work designs to highlight the potential for an alter¬nate cryptocurrency that solves these flaws.

1	Introduction
LFO’s technical ambition is to create a cryptocurrency utilizing a POI algo that FIC created, along with keeping all parties honest, secure, cost-efficient and decentralize. This paper explains why LFO chose proof-of-integrity over proof-of-work and proof of stake alone, to align with the LFO Marketing Models. TRUST IS BUILT INTO THIS THESE BUSINESS MODELS. Everybody wants to help the local and family owned guy.
Over time, the cryptocurrency community has generally become aware of several draw-backs of Bitcoin that spring from its proof-of-work design, including:
1.	the prospect of higher transaction fees in the long run in order to maintain security
2.	the increasing centralization and corporate control of mining
3.	the divergence of interests between miners and Bitcoin holders
These flaws are mounting as Bitcoin matures, and they go against Satoshi’s vision of an open, decentralized network maintained by its participants. They also undermine the principal economic benefit of cryptocurrency - very low transaction fees.
Many in the community believe that Bitcoin’s network effects are strong enough to prevent an alternate cryptocurrency from achieving wide consumer adoption, even if it were technically superior to Bitcoin and solved its shortcomings. Others believe that a strong alternative to Bitcoin’s consensus mechanism can be built.
“There is more than one way in which a distributed ledger system can work, and remu-neration would have to be designed in such a way as to incentivize honest participation in the system without leading to socially inefficient over-investment in transaction verification” (Source: Bank of England [3, p31.])
Proof-of-integrity’s advantages over proof-of-work
Proof-of-integrity, a brand new trust factor model in development, alternate to proof-of-work, fits this bill perfectly. There are two fundamental differences between proof-of-integrity, proof of stake,  and proof-of-work. First, in proof-of-work, miners compete for newly issued coins based not on the amount of electricity and computing resources spent, but rather on the number of coins owned. This crucial difference effectively eliminates the operating costs incurred in proof-of-work mining, replacing them with the capital costs of holding coins. Second, coinbase rewards (called coinstake rewards in proof-of-integrity) are typically not a fixed amount (as in 25 per block in Bitcoin) but proportionate to the number of coins held by the miner and the period of time during which the coins used to stake have remained idle. As such, they are akin to “interest payments” on the miner’s coin holdings. Third, Proof of Integrity, model, by design integrates its own algo to strategically insert fact checks into the transaction process to heighten security of each transaction. 
Based on these  differences, proof-of-integrity completely solves the three problems with proof-of-work, and proof of stake,  as stand alone, that were presented above.
1.	With virtually no operating costs in proof-of-integrity, transaction fees can be far lower than in proof-of-work in both the short run and long run, and regardless of transaction volumes. The only reason they are above zero is to prevent transaction spam.
2.	Proof-of-integrity doesn’t suffer from gradual centralization as proof-of-work does, because all proof-of-integrity algo’s combine the proof of stake into POI verification, so miners earn the same rate of return on their coins (the “interest rate”) regardless of computing hardware or electricity costs.
3.	There can be no misalignment between miners and coin holders, since they are by definition one and the same, if tagged with a poi badge of approval.
Proof-of-integrity also has security advantages over proof-of-work when it comes to resisting 51% attacks from large hostile actors - those whose purpose would be to destroy the network as opposed to simply seeking financial gain. In proof-of-integrity, an attacker would have to acquire 51% of the total coin supply (the value of which would be destroyed in an attack), versus deploying 51% of total computing power in proof-of-work (which computing power could be re-deployed elsewhere after the attack). Once a proof-of-integrity coin achieves a material value, it would be extremely expensive for an attacker to buy up a large percentage of all coins.

Marketing Model using LFO.
LFO (Local Family Owned)
Strategy/Long term plan

LFO stands for:
LOCAL FAMILY OWNED

What is LFO?
LFO is a free local telephone directory for local home owners to use when they want to find local family owned services. We have an 3 click information app, that guides the consumer to the business, resulting in high paying leads to the businesses.

How does LFO work?
Home owners use our free local telephone directory at no charge, and by doing so, local and family owned businesses earn a profit for their niche product or service. 

What are the benefits of using LFO?
-free to use
-easy to use
-makes things simple
-you can trust the service
-makes the buying process better for home owners
-creates incoming leads for local family owned business owners

What rules does LFO have?
LFO only has one rule and that is business owners must be currently reporting their workers to labor and industries in order to have their company on the free telephone directory and this rule was specifically created to protect home owners.

Are large corporations allowed to be on LFO?
Yes. Local means all local services. Family means all family services. The free phone directory does not discriminate in any way shape or form. Any and all local family owned business owners are allowed to benefit from the free telephone directory.

LFO is 100% free to all parties. A local family owned business owner can have their company name, address and phone number on the free telephone directory for no charge and local home owners can go to the web site and use it for free no charge.

How does LFO make money? 
LFO charges local family owned business owners a small monthly fee which is currently $10 per month to add their personal company website to the free telephone directory.

How does LFO get seen?
LFO has marketing experts design create and advertise directly to home owners in multiple ways which include the computer, and also direct marketing campaigns and doorstep pamphlets encouraging home owner to use the free telephone directory.

Where is LFO?
LFO is currently in Bellingham, Washington State.

How big is LFO?
LFO is currently on version one, opened December 15th 2015 and currently has over 1000 users in its target market area.

How big does LFO feel it can service?
LFO is currently only in one county developing model one with the idea that once model one is performing at optimal levels then the proven model will be scaled out with LFO Franchises worldwide. LFO would like to offer its services in all 3000 counties in the USA and globally in the near future.

What is LFO's Model?
•	-creates the best quality leads
•	-creates the most affordable leads
•	-promotes local pride in community
•	-connects home owners to business owners
•	-greatest direct marketing platform on the planet!

This paper has shown that LFO’s carefully chosen proof-of-integrity design, derived from Jeff Grants Full Integrity Coin, which itself was derived from Satoshi Nakamoto’s Bitcoin, is secure, cost-efficient and decentralized in the long run.
The paper has also demonstrated several drawbacks of Bitcoin’s proof-of-work design - including higher transaction fees in the long term, increasing centralization of mining and a divergence of interests between miners and Bitcoin holders - and shown how proof-of-integrity technology completely addresses these drawbacks by introducing two crucial differences:
1.	Rewarding miners based on number of coins owned rather than amount of electricity and computing resources spent - effectively replacing the operating costs of proof-of-work mining with the capital costs of holding coins;
2.	Making mining rewards proportionate to number of coins held and time passed since they last generated a reward, making them akin to interest payments on the miner’s coin holdings.
Since there are virtually no operating costs in proof-of-integrity, transaction fees can be far lower than for proof-of-work in the long run, regardless of transaction volumes. And because all proof-of-integrity miners earn the same rate of return regardless of computing hardware or electricity costs, there is no gradual centralization.
The paper also rebutted the proof-of-work community’s various “nothing at stake” ob-jections to proof-of-integrity and mathematically demonstrated that all commonly cited attack vectors would fail against LFO’s design, which increases security relative to Peercoin and other existing proof-of-integrity currencies in numerous ways, including:
1.	High mining rewards, lower minimum stake age and omission of coin age from the mining equation all incentivize nodes to continuously stake coins over time
2.	Decreased block time, improving user experience and enhancing security against some attack vectors
3.	Causing the stake modifier parameter to change over time for each stake, to substantially increase security against precomputation attacks
4.	Utilizing a client that punishes nodes that attempt to mine on multiple branches with duplicate stakes
As a result, LFO’s design solves both the mounting cost and centralization problems of proof-of-work, and the security and centralization problems with earlier proof-of-integrity coins. As such, LFO is the first peer-to-peer cryptocurrency, regardless of technology, that is secure, cost-efficient and decentralized in the long run.
