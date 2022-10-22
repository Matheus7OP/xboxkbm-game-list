# Xbox Games with Keyboard and Mouse support

This repository holds a crowd-sourced list of Xbox games that offer keyboard and mouse (KBM), along with a list of contributors and their respective contributions. The data hosted here is source for the Xbox KBM website, up-and-running since 2020. 

Xbox KBM is hosted on Netlify (https://xboxkbm.netlify.app/) and Heroku (https://xboxkbm.herokuapp.com/). We're transitioning to Netlify, as Heroku is ending their Free Tier options by November/2022.

## How do I contribute?

Apart from the ways already listed on [Xbox KBM](https://xboxkbm.netlify.app/), you may open a **Pull Request (PR)** in this repository. Your PR should edit both `games.json` and `contributions.json`.  

`games.json` contains the list of games along with some properties such as: a short description on what kind of KBM support the game offers, if the game features crossplay, the link to buy the game on Microsoft Store, etc. You should fill in the information for all fields.

`contributions.json` contains all the list (`games.json`) updates since its creation. Each update has a date, one or more contributors (the ones responsible for providing the information for that update), and the contribution itself (i.e. what was added to the list). You should also fill in the information for all the fields.