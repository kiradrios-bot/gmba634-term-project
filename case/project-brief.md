# PROJECT BRIEF

## Me and my domain
- **Role:** student analyst studying data analytics
- **Field of study:** Sports Marketing and Management/Marketing
- **Domain:** NFL pro football

## The situation (anonymised)
Sports bettors want to be able to make more accurate bets based on the information provided.

## Who decides, and what
- **Decider (role):** a sports bettor
- **Decision:** a moneyline pick: who is going to win the game
- **Options:** the two teams in the game
- **By when:** before the game starts
- **One action:** bet the moneyline on the home team with more rest than its opponent
- **Have I spoken to them?** No. This is my assumption. Everything about the bettor in this brief is *my guess, not confirmed by them*.

## The job to be done (how I know)
- **Their real question:** whether the weather, stadium, and players have an effect on who wins the game. I am not sure if the data supports the players part. *(my guess, not confirmed by them)*
- **What they already know:** team records, betting odds, players, stadium. *(my guess, not confirmed by them)*
- **Their time:** an hour of researching during the week. *(my guess, not confirmed by them)*
- **How I know:** my own assumption. I have not spoken to a bettor.

## Data I can use
**Source:** nflverse `games.csv`, schedules release: <https://github.com/nflverse/nflverse-data/releases/tag/schedules>

| Number | Value | Label |
|---|---|---|
| Games covered, seasons 1999 to 2026 | 7,548 | measured |
| Regular season games | 7,239 | measured |
| Playoff games (120 wild card, 108 divisional, 54 conference, 27 Super Bowls) | 309 | measured |
| Rows with scores | 7,426 | measured |
| Analysis subset: regular season, 2015 on, with scores | 3,045 | measured |
| Rows with `away_rest` and `home_rest` | 7,548 (all) | measured |
| Home team with more rest wins | 277 of 492, 56.3% | measured |
| Equal rest, home wins | 1,058 of 1,971, 53.7% | measured |
| Away team with more rest, home wins | 311 of 582, 53.4% | measured |
| Away team on short rest (4 days or fewer) wins | 81 of 186, 43.5% | measured |
| Home team on short rest wins | 105 of 185, 56.8% | measured |
| Baseline, both teams 7+ days rest, home wins | 1,288 of 2,411, 53.4% | measured |
| Team off a bye (10+ days rest) wins, only one team off a bye | 352 of 646, 54.5% | measured (corrected: earlier 408 of 702 included 56 games where both teams were off a bye) |
| Team with more rest wins, home or away | 548 of 1,074, 51.0% | measured |
| Away team with more rest wins | 46.6% | measured |
| Games with a team on short rest | 186 | measured |
| Rows with temperature and wind | 5,251 | measured |

- **Planned, not counted yet:** rest edge within spread bands (does the edge hold after controlling for opponent strength); rest effect by season; splits by roof, surface, and weather.
- **Estimated:** none.
- **AI-drafted and checked:** none. All numbers were counted directly from the file.

## The AI idea
"AI is supposed to assist."
- What AI would do: UNKNOWN
- What I would do myself: UNKNOWN

## Constraints
- **Deadline:** November 19, 2026
- **Other constraints:** UNKNOWN

## What a hiring manager should conclude
That I spent time being able to understand the data and make an informed decision.

## Unknowns
- Whether a real bettor would confirm the question, knowledge, and time above. I have not spoken to one.
- Whether the data supports the players part.
- How the measured rest numbers connect to the bettor's question (weather, stadium, players).
- What AI would do and what I would do myself.
- Constraints other than the deadline.

## Public-safe check
- **Mine to publish:** yes (my answer). The source is a public nflverse release.
- **Identifying details:** none. The decider is a role, and no real names, employers, clients, or confidential figures appear in this brief.

## My ask, claim and reversal sentence (I add these later)
- **My ask:**
- **My claim:**
- **My reversal sentence:**
