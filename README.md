# Sports-Analytics
This is a project made for a competition on Sports Analytics, conducted by IIT-Jodhpur.


## Problem statement:
Mr. Ronald Koeman is managing FC Barcelona team and he is having a certain dilemma in decision making for which he decides to approach his Sports Analytics team to draw some insights and provide suggestions. Being a member of the analytics panel for the club, you have to assist him with insights. The scout team has come up with an extensive data set (provided in Excel) to support you.

1. Lionel Messi’s contract with the club is ending in 2021 and he is assumed to leave the club once this season ends. The coach is having a great pain in deciding whom to select for the position as there are some important matches ahead and as a coach of a leading club, he is responsible to win the La Liga title for the club and the fans. The coach wants to select some young players (upto 26 years of age) suitable for the position. Based on your analysis of the data, suggest 2-3 players for the position and give the reasoning for the same.

2. The team management is also interested in having an idea of how much the wage the club should fix for the incoming players (that you will be suggesting). The club is having a tradition to pay players based on their Overall Score and at par with other players playing in La Liga with similar ability. You have to help the management in deciding the wage for the players.

3. The club management will also be interested in fixing a transfer clause for the players (that you will be suggesting). Generally clubs fix transfer clause amount based on the player’s Potential. You have to assist them in taking the decision.

## Data:
The dataset provided to us is the FIFA'19 dataset. It has 81 features, which makes it difficult to showcase here (the dataset is present in the repo however, you can view it there). Some othe features are basic information about the player like name, age, country, position, etc. Some are numeric features relating to the player's skill at each position on the field (like right wing, left back, etc.). Some features are numeric estimates of various skills of the player, like Dribbling, Ball-control, Agility, etc. We're also given their wages and transfer clause that is required in Problem Statement 2 and 3



## Our approach:

#### Part 1:
Important consideration points:
1) Lionel Messi is a regular and a very important player on the field for FC Barcelona. We need someone to replace him in the team immediately, someone who can take to the pitch immediately.

2) FC Barcelona being a pretty big club, wouldn’t mind paying for the transfer clause of excellent players with capabilities like Messi. Hence, their current contract validity won’t really matter.

3) Young players required (Age ≤ 26)

What we did:
Messi is a Right Wing player by position, but plays mostly in attacking zones, scoring goals. For his replacement, we’d desire the same characteristics: Attacking and Midfield presence.

We **innovatively** generated a **new metric** for “**Difference from Messi**” based on the ratings for RF, RW, RS, RAM, and the various ratings for a player’s skill (only related to Attacking and midfielding).
