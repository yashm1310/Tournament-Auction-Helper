# Tournament Auction Helper

### This code comes in handy for organizing auctions for tournaments with many teams.

In this code:
1. Take the list of players as an input in form of excel sheet and convert it into a dataframe.
2. Take the input for number of teams and the size of the purse.
3. Shuffle the list and then select names from it randomly in order to keep the auction fair and then auction the player. If sold then add the player to the respective team, subtract their purse amount by the price of the player and then increment the team's player count else add him to the unsold list.
4. Display the Teams , Purse amounts and Player count of each team.
5. Shuffle the unsold list and then select names from it randomly and distribute the players in teams so everybody gets selected by a team. 
6. Display the Final Teams and Player count of each team.

### Libraries used: 
1. Pandas

### Modules that can be added:
1. The final results can directly be stored into a excel sheet.
2. Statistics of the player and other information can be displayed alongside the name during the auction.
