# SCR worksheet

## Box 1: Audience and ask
> Audience: a sports bettor
>
> I am asking the sports bettor to adopt betting the moneyline on the home team with more rest before kickoff, by the Week 11 games on November 19.

**Test:** OK on the second version. The first version failed "by WHEN" ("before kickoff" was when each bet is placed, not a deadline); I added the date.

## Box 2: Situation
> The data covers 7,548 NFL games from 1999 to 2026, and every game records how many days of rest each team had. Rest is not equal: most teams play on 7 or more days rest, some after 4 or fewer, others 10 or more days off.

**Test:** OK on the second version. The first version said "seven days" and "four days"; my counts are 7 or more and 4 or fewer.

## Box 3: Complication and the one chart
> What changed: rest now shows up in the results. A home team with more rest wins 56.3 percent of the time, 277 of 492, measured, against 53.7 percent on equal rest, 1,058 of 1,971, measured.
>
> The one chart: a horizontal bar chart titled Home teams win more with more rest, bars starting at zero, values labelled on the bars. Home team has more rest, home wins 56.3 percent, measured. Equal rest, home wins 53.7 percent, measured. Away team has more rest, home wins 53.4 percent, measured.

**Test:** OK on the third version. The first version's third bar read as the away team's win rate; 53.4% is the home win rate (311 of 582). In the third version I removed the 43.5% away-short-rest figure: 185 of its 186 games are already inside the equal rest bar (both teams short), so charting it would double count them. It stays as a supporting finding in the case, not in Box 3.

## Box 4: Question
> So should we bet the moneyline on the home team with more rest before kickoff?

**Test:** OK.

## Box 5: Recommendation
> Verb: adopt the rest rule for moneyline picks. Owner: the sports bettor. Date: by the Week 11 games on November 19. Cost: $0 beyond the bets the bettor already places. The data is free and public from nflverse. The rule changes which team to pick, not how much to stake. Alternative rejected: betting on any team with more rest, home or away. The team with more rest wins only 51.0 percent of the time overall, 548 of 1,074, measured, and an away team with more rest wins only 46.6 percent, 271 of 582, measured.

**Test:** OK. Verb, owner, date, cost and its source, and the rejected alternative are all present. Second version: the Tableau Public dashboard sentence is removed.

## Box 6: Reversal
> I would reverse this recommendation if the home team with more rest wins 53.7 percent or less of the time within spread bands, found in the spread bands built from the spread_line column in games.csv.

**Test:** OK. Number: 53.7%. Place: spread_line in games.csv. Change: the ask would be dropped. Spread bands are planned, not counted yet; I checked that spread_line exists and has a value for all 3,045 games from 2015 on.

## ASSUMPTIONS YOU MADE
- Box 1: I treated "by the Week 11 games on November 19" as the WHEN.
- Box 6: I read "the change it would force in my ask" as dropping the ask; the box does not say so in words.

## Checked by me
- Week 11, 2026: 13 games, on November 19, 22 and 23. The November 19 game is Indianapolis at Houston, Thursday. Checked in games.csv.
- spread_line exists in games.csv, with a value on all 3,045 games from 2015 on.

## NOT VERIFIED: you must check
- 7,548 games, 1999 to 2026: games.csv.
- 277 of 492 (56.3%), 1,058 of 1,971 (53.7%), 311 of 582 (53.4%): games.csv, analysis subset (regular season, 2015 on, with scores).
- 548 of 1,074 (51.0%), 271 of 582 (46.6%): games.csv, analysis subset.
- 185 of the 186 away-short-rest games fall inside the equal rest bar: games.csv, analysis subset.
- nflverse data is free and public: the nflverse schedules release page and its license.

## AI USE LINE
I wrote every SCR box, number and date, and checked the Week 11 date and the spread_line column myself; Claude (Anthropic) tested each box against its rule and arranged them into this worksheet.
