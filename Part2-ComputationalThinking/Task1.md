
N = 4987 
1) How many matches would it take to determine the winner.
2) Number of games played by winner by the time winner is determined. 

I tackled this one by starting with a very small odd number: 3. Since the match is of knockout type, the winner will have to win all of the matches. 

When N = 3, say A, B and C, the first match (`no_of_matches = 1`) can be between AB or AC or BC (order does not matter). Let's say AB play. That means the loser doesn't get to play another match. Say A wins. A now has to play against C (update `no_of_matches = 2`). Whoever wins now wins the title. Thus, the variable `no_of_matches` holds 2 matches as the answer.

Another way is to cut the matches by half each time (since the losers are out). If there are 100 participants, in the first round there will be 50, then 25, then 12 (12 from 24 and 1 extra participant), then 6, then 3, then 2, then the final 1 match. i.e. 99 matches.

This rule can be propagated to any number.
1) Ans: 4987 -1 = 4986

2) For this one, I found out a rule which is `N = 2*M - 1`, where `N` is the total number of participants and M is the *MAXIMUM* number of games played. Note that the winner can be decided by only 1 match (for the odd one that doesn't get a pair) as well as `M` matches that can be calculated using the above equation.

Thus, for `N = 4987`, 

`M = (N + 1) / 2` (Integer division) <br>
`M = 4988 / 2` <br>
`M = 2494`

Hence, the Number of games played by winner by the time winner is determined varies from 1 to 2494.
---