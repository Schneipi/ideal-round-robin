# Ideal Round Robin
Given ***n*** teams, every round robin schedule (***n***-teams.txt) has the following properties:

## n is even

1. Mirrored double round robin schedule: Same games in round ***k*** and round ***k+n-1***, except inverted home advantage.
1. Total number of breaks (consecutive home/away games) is a minimumand equals ***3n-6*** [de Werra 1981].
1. First ***n-1*** rounds on their own compose a single round robin schedule with a minimum of ***n-2*** breaks [de Werra 1981].
1. No breaks in rounds ***2*** and ***n-1***, entailing that every team has precisely ***1*** home game in the first ***2**** rounds and precisely ***1*** home game in the last ***2*** rounds.
1. No consecutive breaks, entailing no more than ***2*** home/away games in a row for every team.
1. Teams ***1*** and ***2*** have ***0*** breaks, all other teams have ***3*** breaks.
1. The higher the team number, the lower the round number containing the first break for the team.

## n is odd

1. Mirrored double round robin schedule: Same games in round ***k*** and round ***k+n***, except inverted home advantage.
1. Total number of breaks (consecutive home/away games without considering bye rounds) is a minimum and equals ***n*** [de Werra 1981].
1. First ***n*** rounds on their own compose a single round robin schedule with a minimum of ***0*** breaks [de Werra 1981].
1. An optimum amount of ***n-1*** teams have precisely ***1*** home game in the first ***2*** rounds and precisely ***1*** home game in the last ***2*** rounds.
1. No consecutive breaks, entailing no more than ***2*** home/away games in a row for every team.
1. Every team has exactly ***1*** break.
1. The higher the team number, the lower the round number containing the first break for the team.

<sub>The schedules in this repository were created based on optima extracted from the literature, with the purpose to serve as basis for sports planning and scheduling projects.</sub>
