# Differentially-Private-POS
Differentially Private Proof of Stake Protocol that anonymizes the stake for individual validators in the system. 

This was a course project for COMPSCI 590 (Blockchain Consensus) and was worked on by David Pujol, Pranay Jain and Rathi Kashi. 

### Abstract

Proof-of-Stake (PoS) is a mechanism for block proposal through leader election based on the party’s
stake in the system. Current PoS-based protocols inadvertently disclose information about the
amount of stake a validator has in the system. This is equivalent to discovering the wealth of the
validators in the system, which is a breach of privacy and could potentially open up the network to
selective attacks. We propose a Differentially Private Proof of Stake mechanism that anonymizes
the stake for individual validators in the system. Our method performs leader election using a noisy
stake in each round, which provides privacy that does not degrade over time. Through simulations,
we show that our mechanism makes it hard to recover one’s stake while ensuring that the fairness
in leader election is not affected over a sufficiently long time.

#### The project report and code for simulations can be found in this repo. 
