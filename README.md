# Mintopoly! Money Airdrop

This repo records the airdrop results for the Mintopoly! Money awards. Each week, the top X finishers recieve an airdrop of our ERC-20 token (Mintopoly! Money) based on their net worth and finish position. The distribution formula works like this...

1. Tally net worth of combined 250 players
2. Loop through each player, in order of rank. For each:
	1. Divide their net worth by total net worth
	2. Multiply this by the airdrop size to get their payout amount
	3. If their share is > 1% of airdrop size, cap their payout at 1%
	4. Subtract this player's payout from total payout remaining and their net worth from total net worth remaining.
	5. Repeat with each successive player with these new totals 


Each weekly calculation is posted in a txt file here, and airdrop transactions are recorded below. Note that transactions may not occur immediately after reach round – they may be batched for 1-4 rounds (i.e. 1-4x per month in order to save gas fees).


### Airdrop Transactions

Check back after round one!
