# round-robin-schedules
<b>Given n teams, every round robin schedule has the following properties:</b>

<b>n is even</b>

1) Mirrored double round robin schedule: Same games in round k and round k+n-1, except inverted home advantage.<br/>
2) Total number of breaks (consecutive home/away games) is a minimum and equals 3n-6 [de Werra 1981].<br/>
3) First n-1 rounds on their own compose single round robin schedule with a minimum of n-2 breaks [de Werra 1981].<br/>
4) No breaks in rounds 2 and n-1, entailing that every team has precisely 1 home game in the first 2 rounds and precisely 1 home game in the last 2 rounds.<br/>
5) No consecutive breaks, entailing no more than 2 home/away games in a row for every team.<br/>
6) Teams 1 and 2 have 0 breaks, all other teams have 3 breaks.<br/>
7) The higher the team number, the lower the round number containing the first break for the team.<br/>

<b>n is odd</b>

1) Mirrored double round robin schedule: Same games in round k and round k+n, except inverted home advantage.<br/>
2) Total number of breaks (consecutive home/away games without considering bye rounds) is a minimum and equals n [de Werra 1981].<br/>
3) First n rounds on their own compose single round robin schedule with a minimum of 0 breaks [de Werra 1981].<br/>
4) A maximum of n-1 teams have precisely 1 home game in the first 2 rounds and precisely 1 home game in the last 2 rounds.<br/>
5) No consecutive breaks, entailing no more than 2 home/away games in a row for every team.<br/>
6) Every team has exactly 1 break.<br/>
7) The higher the team number, the lower the round number containing the first break for the team.<br/>
