Science (Verification) Prize
============================

* Repository with:
	- Description of the problem
	- The data
	- Example code that reproduces the baseline
	- Instructions for how to get the bot to run the code (part of the example code)
	- Instructions for how the results should be output (so the bot can pick it up)

Have people:
* fork it, modify the base with their model/parameters, add code in, etc
* Create a PR when they are happy with the code + their local results,...
* Bot will spin up AWS, run the code and grab the results, then display them as part of the PR
* If a new PR comes in that beats an existing PR, it should comment/link to the old PR so that
  the user who was previously #1 is alerted about the new leader.

* Add the result 'score' to some benchmark table in the example?
* At the end of the competition, accept the PR with the best score?

