# Github GraphQL

[![style: styled-components](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/styled-components/styled-components)
[![Build Status](https://travis-ci.org/martinbagshaw/Github-GraphQL.svg?branch=master)](https://travis-ci.org/martinbagshaw/Github-GraphQL)
[![codecov](https://codecov.io/gh/martinbagshaw/Github-GraphQL/branch/master/graph/badge.svg)](https://codecov.io/gh/martinbagshaw/Github-GraphQL)

A first foray into using Github GraphQL API with React Apollo.

View the live app here:

[https://martinbagshaw.github.io/Github-GraphQL/](https://martinbagshaw.github.io/Github-GraphQL/)
> please note that to use the live version of the app, you must login with your Github account details. This generates a temporary personal access token. See [Todo](#todo)

<img width="757" alt="Screenshot 2020-10-27 at 22 52 03" src="https://user-images.githubusercontent.com/28146666/97509951-8b14cc80-197b-11eb-9f3a-4db19f42a959.png">

## To get running locally:
- clone the repository
- `npm install`
- go to your github account and [generate a personal access token](https://help.github.com/en/articles/creating-a-personal-access-token-for-the-command-line)
- create an `.env.local` file in the root, with your access token in the following format:  
  `REACT_APP_TOKEN=your-token-here`. Note that your token does not require quotes around it
- `npm start` to view the app locally at [http://localhost:3000/](http://localhost:3000/)

### Using this app:
**If Viewing on Github Pages:**
- Enter your Github username and password to access the search engine, then...

1. Search for a **User's Details**
- a) Enter a valid github **Username** in the text input field
- b) Press 'Submit' (with **Get User's Details** toggled)
- c) Press 'Show More' to view more details

2. Search for a **User's Repositories**
- a) Toggle **Get User's Repositories** (with a valid username entered)
- b) Use the filter buttons to see repositories the user has authored, forked, and contributed to
- c) Press on a right arrow '>' from a repository to view more details about it
- d) Press on a left arrow '<' to go back to the list of results
