# Probabilistic Rating system

The data you can find through this link: https://www.dropbox.com/s/s4qj0fpsn378m2i/chgk.zip 

- build a rating list that is able to non-trivially predict the results of future tournaments;
- at the same time, since ChGK is a hobby, and there are no contracts here, players constantly move from team to team, a strong player can play for another team for one tournament, etc.; therefore, the unit of the rating list should not be a team, but a separate player;
- and what greatly simplifies the task and translates it into the field of homework for the EM algorithm is the nature of the data: starting from some point, all the team's survey results began to be entered into the results database, i.e. there will be entries in the data like “which team answered which question correctly".