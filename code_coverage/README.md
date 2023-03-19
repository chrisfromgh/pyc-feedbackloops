# Code Coverage
https://2023.pycascades.com/program/talks/fear-the-mutants-love-the-mutants/

## Mutation Testing???

code coverage is how much the source of a code is run when a test suite is run

tests can be misleading.

goodharts law https://en.wikipedia.org/wiki/Goodhart%27s_law how do we know our tests are good?

who watches the watchers 

mutation testing is taking production code and making it into a "mutant" https://www.techtarget.com/searchitoperations/definition/mutation-testing#:~:text=Mutation%20testing%2C%20also%20known%20as,cause%20errors%20in%20the%20program.

this puts our tests in to evaluation, by making our tests try to detect changes 

https://github.com/boxed/mutmut

`mutmut html` can provide.an hmtl generated page of all the tests and data

100% is irrelevant, the insight is important

start with a subset of a project

ideally to use cloud resources because it takes time to run

create a github action to use the cloud resource in order to run mutmut and run the tests, that way you can run the tests and then get the html.

can be useful to do github actions in order to check and run on multiple OS's and versions

