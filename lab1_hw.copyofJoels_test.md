---
title: "Lab 1 Homework Copy of Joel's"
author: "A copy of Joel Ledford's as a test"
date: "Winter 2019"
output:
  html_document:
    keep_md: yes
    theme: spacelab
---
##This is copied from Joel Ledford.  I did not create this.

## Instructions
Answer the following questions and complete the exercises in RMarkdown. Please embed all of your code, keep track of your versions using git, and push your final work to our [GitHub repository](https://github.com/FRS417-DataScienceBiologists). I will randomly select a few examples of student work at the start of each session to use as examples so be sure that your code is working to the best of your ability.

1. Navigate to the R console and calculate the following expressions.  
  + 5 - 3 * 2  
  + 8 / 2 ** 2  
  
2. Did any of the results in #1 surprise you? Write two programs that calculate each expression such that the result for the first example is 4 and the second example is 16.  


3. You have decided to use your new analytical powers in R to become a professional gambler. Here are your winnings and losses this week.

```r
blackjack <- c(140, -20, 70, -120, 240)
roulette <- c(60, 50, 120, -300, 10)
```

a. Build a new vector called `days` for the days of the week (Monday through Friday). 

```r
days <- 
```

We will use `days` to name the elements in the poker and roulette vectors.

```r
names(blackjack) <- days
names(roulette) <- days
```

b. Calculate how much you won or lost in blackjack over the week.

```r
total_blackjack <- sum(blackjack)
total_blackjack
```

c. Calculate how much you won or lost in roulette over the week.  


d. Build a `total_week` vector to show how much you lost or won on each day over the week. Which days seem lucky or unlucky for you?

```r
total_week <- 
```

e. Should you stick to blackjack or roulette? Write a program that verifies this below.


## Push your final code to [GitHub](https://github.com/FRS417-DataScienceBiologists)
