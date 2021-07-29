# Mintopoly! Money Airdrop

This repo records the airdrop results for the Mintopoly! Money awards. Each week, the top X finishers recieve an airdrop of our ERC-20 token (Mintopoly! Money) based on their net worth and finish position. The distribution formula works like this...

1. Tally net worth of combined top n (typically 250) players
2. Loop through each player, in order of rank. For each:
	1. Divide their net worth by total net worth
	2. Multiply this by the airdrop size to get their payout amount
	3. If their share is > 1% of airdrop size, cap their payout at 1%
	4. Subtract this player's payout from total payout remaining and their net worth from total net worth remaining.
	5. Repeat with each successive player with these new totals 


Each weekly calculation is posted in a txt file here, and airdrop transactions are recorded below. Note that transactions may not occur immediately after reach round – they may be batched for 2-4 rounds (i.e. 2-4x per month in order to save gas fees).


## Airdrop Transactions

### Round 1 (7/28/21)
**Mintopoly Money Airdrop  (1m to top 250)**
* https://etherscan.io/tx/0x692d3a5da44e3669e0c254377be57b159a9c25114a848d607b13bea795dd7767

**Mintopolist Card (Top Place)**
* https://etherscan.io/tx/0xb4f4201ac9635f3a852005b25e2917df7d4cb0ea454b881dd57c8251bb036150

**Dale Card (Validator Node Bonus)**
* https://etherscan.io/tx/0x6d76ba6b0794808e6bd52079ac698438534090da3e7f2a86ab8ce6619ea1b0ff
* https://etherscan.io/tx/0xc238897361f4d3d12cee31ea83ae324ffe83d8a9dedcc73a92010286c9e60e58
* https://etherscan.io/tx/0x9d81881a469b98cc2efe80c6c40b48842d29bf334abb7a3c2073e4e386e35da8
