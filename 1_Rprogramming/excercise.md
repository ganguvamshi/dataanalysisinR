## Assignment for Basic R

### Task1 : Read the titanic dataset from `/data` folder
load the data into R and describe the columns

### Task2 : Count total number of passangers
### Task3 : how many passangers are survived the sinking
Calculate the percentage of passangers who survived 
### Task4 : how many first class passangers who survived the sinking
### Task5 : measure the percentage of survivors who were female
### Task6 : Test hypothesis (Home Work)
hypothesis: The proportion of females onboard who survived the sinking of the Titanic was higher than the proportion of males onboard who survived the sinking
steps:
- Construct a two-way contigency table between Sex and survived columns
- Run the `chisq.test` function on the table
- see the p-value obtained and conclude

Hint: use [`xtabs`](https://homerhanumat.github.io/tigerstats/xtabs.html) function from [`pysch`](https://cran.r-project.org/web/packages/psych/index.html) library for more group wise summary
