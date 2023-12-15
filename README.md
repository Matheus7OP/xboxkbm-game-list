# Xbox Games with Keyboard and Mouse support

This repository holds a crowd-sourced list of Xbox games that offer keyboard and mouse (KBM), along with a list of contributors and their respective contributions. The data hosted here is the source for the Xbox KBM website, which has been running since 2020. 

Xbox KBM is hosted on Netlify (https://xboxkbm.netlify.app/). We've transitioned from Heroku since they ended their Free Tier options in November/2022.

## How do I contribute?

Apart from the ways already listed on [Xbox KBM](https://xboxkbm.netlify.app/), you may open a **Pull Request (PR)** in this repository. Your PR should edit both `games.json` and `contributions.json`.  

`games.json` contains the list of games along with some properties such as: a short description on what kind of KBM support the game offers, if the game features crossplay, the link to buy the game on Microsoft Store, etc. You should fill in the information for all fields.

`contributions.json` contains all the list (`games.json`) updates since its creation. Each update has a date, one or more contributors (the ones responsible for providing the information for that update), and the contribution itself (i.e. what was added to the list). You should also fill in the information for all the fields.

Example of a valid PR: https://github.com/Matheus7OP/xboxkbm-game-list/pull/1
