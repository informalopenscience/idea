# idea

Branch     |[GitHub Actions](https://github.com/tresinformal/game/actions)                                       |[![Codecov logo](man/figures/Codecov.png)](https://www.codecov.io)
-----------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------
`master`   |![check](https://github.com/informalopenscience/idea/workflows/check/badge.svg?branch=master)   |[![codecov.io](https://codecov.io/github/informalopenscience/idea/coverage.svg?branch=master)](https://codecov.io/github/informalopenscience/idea/branch/master)
`develop`  |![check](https://github.com/informalopenscience/idea/workflows/check/badge.svg?branch=develop)  |[![codecov.io](https://codecov.io/github/informalopenscience/idea/coverage.svg?branch=develop)](https://codecov.io/github/informalopenscience/idea/branch/develop)
`richel`   |![check](https://github.com/informalopenscience/idea/workflows/check/badge.svg?branch=richel)   |[![codecov.io](https://codecov.io/github/informalopenscience/idea/coverage.svg?branch=richel)](https://codecov.io/github/informalopenscience/idea/branch/richel)

 * Branches are ordered `master`, `develop`, then topic branches alphabetically

![informalopenscience logo](informal_open_science_logo.jpg)

:warning: everything on this page is still a draft :warning:

Science, done informally and professionally.

## Goal

To do science informally and professionally.

 * Informally: work comes first, no money, no deadline
 * Professionally: the best Open Science practices

## Researching via Discord

We do our science, while chatting on Discord.
To join, send Richel a Discord Friend Request: `richelbilderbeek#9002`.
He'll add you to the informalopenscience server.

## Meetings

 * Date: Weekly, every ?Friday
 * Time: ?17:00-19:00
 * On Discord

We follow this timetable:

What             | Time
-----------------|------
Doors open       | 17:00
Work starts      | 17:15
Break time!      | 18:00
Work continues   | 18:15
End of lesson    | 19:00

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

In case it is undesirable to email Richel,
contact [need to find other one].

## Short-term schedule

Next meeting:

Timespan    |Activity
------------|--------------------------------------------------------------------------
17:00       |Door opens
..          |Do Issues
17:45-18:00 |Break
..          |Do Issues

 * Note that `xx` and the other variables can be in range `00` to and including `59`. 

## Long-term schedule



Date       |Activity
-----------|--------------------------------------------------------------------------
.          |collect ideas and team members, [YouTube: Why Open Science](https://youtu.be/s4hsBBhEabs)
.          |choose project
.          |practice workflow, [GitHub: How to do Open Science](https://github.com/richelbilderbeek/how_to_do_open_science_example) [YouTube: setup workflow](https://youtu.be/mEvYOt8VOFU)
.          |write first version, focus on hypotheses, [YouTube: Hypotheses](https://youtu.be/7BfZqdn2eYc)
.          |write second version, focus on methods, [YouTube: Hypotheses](https://youtu.be/Zj1fb-Izrko)
.          |rewrite for pre-registration
.          |pre-register article, until acceptance
.          |do experiment
.          |write down results
.          |publish results

## FAQ

### Science

#### Which projects are already suggested?

 * Use AI to classify the correct 
   [Elephantiasis](https://en.wikipedia.org/wiki/Elephantiasis) 
   stage from a photo.
   Elephantiasis is a 7 stage disease that 150,000 people have today.
   From a picture, as taken by a smartphone,
   the stage needs to be predicted, as treatment differs per stage. 
   The group of Alex Kwarteng in Ghana will deliver a labelled dataset.
   It is assumed this has never been done yet.
   The accuracy of the predictions is estimated to be low, as
   the exterior of a leg has few features.
 * Compare the predictions of three epitope prediction programs,
   ([see here for an example of two programs](https://github.com/richelbilderbeek/ep_vs_mhcn)).
   Based on the output of the three programs, determine if the three tools
   agree on their predictions. This is a similar problem as when comparing
   the output of noisy Celsius, Fahrenheit and Kelvin thermometers.
 * [Solve a text-adventure book](https://github.com/richelbilderbeek/CityOfThieves/tree/master/Article#city-of-thieves-solved).
   Determine the optimal solution how to play the game.

#### How do we pick which project?

The first step is to reach consensus:

The exact procedure:
 * Each team member can suggest any number of projects.
 * Each project is presented in 5 minutes max.
 * Each team member can vote on each project he/she would enjoy to do.
 * The project that has all team members on board wins. 
   In case of a draw, there are voting rounds between the winners, 
   until there is a winner.
   When there is no winning project, this cycle repeats at a next meeting

If consensus cannot be reached, there is no other option than to do voting:

The exact procedure:
 * Each team member can suggest any number of projects.
 * Each project is presented in 5 minutes max.
 * Each team member can vote on each project he/she would enjoy to do.
 * The project with the most votes wins. 
   In case of a draw, there are voting rounds between the winners, 
   until there is a winner.

#### What is meant with Open Science?

Open Science is a diffuse concept.
We follow these rules:

 * Open communication: communication via GitHub Issues
 * Open workflow: git keeps a history of our work, both for the paper,
   as well as the experiment
 * Open attribution: git shows that all authors contributed substantially
 * No HARKing: we publish our article, with Introduction and Methods
   before we do the actual experiment

#### Where is the paper pre-registered?

The only known candidate for now is [https://osf.io](https://osf.io).

The team will vote where the paper is pre-registered.

#### What is the intended journal?

A platinum journal, in which one can publish open access articles for free.

The team will vote which journal.

 * Because the team is informal, there can be no money involved.
 * Because the team does open science, the article must be open access.

### Work

#### What is meant with informal?

 * Work goes first: you are always excused to be absent
 * Having a beer is fine

#### How can I contribute?

You can help write the paper or the code or both. 

#### I am a newbie researcher. What must I do?

Welcome to the team! Here is a more-or-less-chronological (i.e. if you
get stuck, start working on the next one) list of what to do:

 * Become an IOS team member
 * Modify README.md on master branch
 * Make a branch for yourself via the GitHub web interface
 * Modify README.md on your local harddrive on your own branch
 * Add your branch's badges to the README.md

When you feel comfortable with the workflow, you become a junior researcher!

#### I am a junior researcher, what should I do?

Junior researcher are comfortable with the workflow,
especially git and GitHub. 

If you want to write the paper:

 * Write :-)

If you want to work on the code:

 * Do Issues labeled 'good first Issue' or 'junior'

Golden rules:

 * Whatever you work on, always be assigned to an Issue
 * Whatever code you develop, always be working to fix a test,
   unless you work on graphics
 * If all tests pass, we are -by definition- happy

#### I am a medior researcher, what should I do?

A medior developer 

 * writes tests and creates Issues for juniors and themselves
 * does code reviews
 * works on more complex issues, such as improving the architecture of
   the code or improving the continuous integration tools (whatever those are :-))
 * see the bigger picture of the code and the team.

You know what to do :+1:

