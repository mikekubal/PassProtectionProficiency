# PassProtectionProficiency

Abstract:
The PPP statistic might be a quarterback's and general manager's new best friend.

The average NFL team pays it top 5 lineman a total of about $23 million per year
for a 49% chance of an offensive line related negative event on a passing play (lineman beat, or quarterback hurried or hit or sacked).

Leveraging PPP, a team could conceivably reduce their chance of a negative event to 19% by spending an additional $4 million dollars per year.
If a team could sign the 5 players with the higest PPP scores, their salaries would total about $27M dollars per year.

Interestingly, if a team were to sign the 5 highest paid offensive lineman, their salaries would total about $74 millions dollars per year, but the chance of a negative event would still be a whopping 40%.

Initial exploration of player data showed that experience (using age as a proxy) is 
better correlated with PPP than athleticism (as measured by combine data), though salary is more correlated with athleticism. 

The analysis suggests that NFL teams are not optimal aligning offensive line salaries with PPP. 
The mystery of how offensive lineman salaries are set is not revealed by the analysis.
This analysis did not inlcude run blocking proficiency which could explain some of the seeming misalignment of salary with performance.

Perhaps the most novel and hopefuly useful aspect of the analysis is that it provides support for my 'weak-link-in-the-chain' theory. 
Smart defensive coordiantors have figured out that it only takes one defender in the backfield to blow-up a play.
Fittingly they will look for the match-up against the weak link in the offesnsive line. 
Knowing this offensive lines should attempt to balance the PPP across the line, maximizing the PPP of their weakest player, 
and eliminating weak-links.
The analysis shows lines with this characteristic do this achieve a better overall team PPP.

However, this may be a happy accident for some of these teams. 
Looking at the average offensive line salary distribution across teams, 
one might conclude that having a tackle 'super' block his defender somehow offsets the guard's poor pass blocking.

I am exploring building a Bayesian predictive model that leverages PPP
and can calculate risk of negative event in real-time based on context of the play: 
1. play called
2. specific offensive lineman in game
3. field postion
4. score and quarter
5. specific defenders in game
6. defensive alignment
7. QB mobility
8. QB decision-making

Please email me at mikekubal@yahoo.com with any suggestions, feedback or errors in the code.

This repository contains notebook and data files for submission to Kaggle NFL Big Data Bowl 2023 contest, https://www.kaggle.com/competitions/nfl-big-data-bowl-2023
