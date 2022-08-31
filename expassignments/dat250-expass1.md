# Raport expass1 

## Problems encountered

First problem I encountered was in the step to check an in dept information about the Postgres database. When the information came up I saw that the connection said 0/20 instead of 10/20. When I then ran “heroku pg:psql” I got an error and could not connect to the remote database. To fix this problem I restarted the Postgres database. I then ran the command “heroku pg” again and could see that the connection said 10/20 like it should and the next commands where working again. 

## Validation process

When setting up the software development environment we had a really simple manual to follow and it was easy to check that that every output in the terminal would match what the manual had. Another way that I validated the process was to check the environment by opening it, either the heroku environment when I was setting up that and the local environment when setting that up. If it did not open correctly it means that something had gone wrong. 

## Technical problems with Heroku platform and other problems

There was not really any technical problems with setting up Heroku and navigating around the platform. Not really much problem with the assignment. Only thing that took a while was all the installations that had to be done before the actual Heroku environment setup.

## URL
[Heroku app link](https://shrouded-thicket-90209.herokuapp.com/)
