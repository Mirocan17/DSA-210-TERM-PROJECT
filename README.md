# DSA-210-TERM-PROJECT
Do Tanking NBA Teams Really Get What They Want? Exploring the Draft Dreams and Realities Behind Losing Seasons 
## Project Overview
Every NBA season, certain teams lose their games on purpose, sacrificing wins today for the hope of future superstar. This debatable strategy, popularly known as tanking, leads to a very important question with two opposite opinions among fans: Do tanking NBA teams really get what they want? 

In this project, we will explore whether sacrificing a teams entire season for the draft worths or not. We will analyze NBA regular season data and NBA draft data including team records, draft results and player performances for each NBA year. We will also try to understand that whether that lottery system is just or not.

## Motivation
Every summer, different from most of the other popular sports in the world, more than 50 new young and talented basketball players comes to the NBA. Especially top picks of those drafts are destined to change the destiny of the league and their franchises. Some succeeds but some of them are just lost after couple of years. In the draft lottery, all of the least successful teams and some mid block teams have chance to get top 3 picks with different percentages. Some teams has no choice other than tanking due to the lack of talent in their squad but some teams do it on purpose because of the generational talents in the draft. Even if its logical to get a generational talent for the franchises future, losing games on purpose is dissapointing for the fans and there is no guarantee that the team will get what they want. Also, i have been following NBA right now for around 7 years and most of the contending teams didnt change a lot so i really want to learn do tanking really change destinies of franchises.

## Objectives
• Examining the details of the draft and the lottery system and compare it with the previouss systems.

• Determine how many of these teams are truly getting the player that they want.

• Determine when its logical for an NBA team to do tanking.

• In what possibilty that the drafted NBA player and NBA team win something.

## Data Collection
This project will be mainly based on 3 datasets. The datas to be found:

### NBA Regular Season Statistics

•NBA Teams : The records of every NBA team will be collected to find the tanking teams for each year.

•Standings by Conference : The draft positions for the teams which are in the lottery are determined based on which conference they are in and their position in that conference.

### NBA Draft Lottery Statistics

•Percentages : The expected percentages will be found to analyze it in terms of logic and compare different lottery systems with each other.

•Lottery Results : The lottery results will be collected to compare it with the expected percentages and which teams got what they wanted. 

### NBA Draft results and the performances of the players.

•Draft Order : Analyzing the data to see which player is selected in which order in the draft.

•Accolades of Players : The careers of especially top picks will be analyzed to see how many of them succeed and meet expectations.

## Data Process
1.Data Cleaning

•Merging : The team name, draft order and players drafted will be merged, linking every teams record in a season with their draft results in the upcoming year.

•Missing or Wrong Data : In huge datasets, some missing or wrong values can occur. Those errors will be standatized.

•Adjustments : New columns for the data can be added for different anaylsis.

2.Explatory Data Analysis (EDA)

•Visualization : Maps, graphs, charts will be used to visualize the relationship between team performance, draft order and player perrformance. Basic statistics will be computed to relate with the data.

## Hypothesis Testing Summary

This project evaluates the effectiveness of NBA tanking through three key statistical tests ($\alpha = 0.05$):

## 1. Rebuilding Success (The 3-Year Rule)
$H_0$: Tanking teams and non-tanking teams have similar win percentages after 3 years.

$H_1$: Tanking teams significantly outperform others after a 3-year rebuilding period.

Method: Independent Two-Sample T-Test.

## 2. The "Top 3 Pick" Factor
$H_0$: Securing a Top 3 draft pick does not significantly improve a team's win percentage.

$H_1$: A Top 3 pick leads to a significant performance boost in following seasons.

Method: Paired T-Test.

## 3. Impact of 2019 Lottery Rule Changes
$H_0$: The effectiveness of tanking remained the same after the 2019 lottery odds change.

$H_1$: The strategy became significantly less effective after the 2019 rule changes.

Method: Correlation Analysis / ANOVA.
## Tools and Technologies
Python : Main programming language for all steps of the project providing visualization and data processing.

Pandas : Used for further processing operations on the data.

Websites : To found accurate and reliable data for the project.

## Expected Outcome
This analysis will be helpful to understand if tanking is an effective strategy or just a gamble.



