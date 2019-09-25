# Loan Data from Prosper
## by Alex Paz


## Dataset

The data consists of 113,937 loan listings between 2005 and 2014 on Prosper, a peer-to-peer lending marketplace. For each listing, there are 81 features are available.

The dataset is curated by Udacity and was obtained directly from them as part of the class projects.

## Summary of Findings

Initially, I was mostly interested in finding out how borrowing from friends influence on one's default rate. During exploration, I learned that only 26 listings had been funded by 5 friends or more, making it too small a sample. So instead, we focused our efforts on understanding the influence of variables on:

- Borrower's interest rate
- default and chargedoff percentages

After examining a few of the variable distributions, we noticed that a significant part of the listings is comprised of debt consolidation loans. In other words, borrowers were refinancing existing debts rather than borrowing for new projects or expenses.

One of the usually key aspects regarding debt, the Debt to Income ratio, shows no strong signs of correlation to neither BorrowerAPR nor (default/chargedoff) rates (LoanStatus categories). Only when ratio approaches 0.3, it starts to push Borrower's interest rates up.

The main finding was the influence of a higher income on reducing both interest rates and default proportions.

Check out the [code for analysing the Prosper loans here](https://alexmpaz.github.io/data-visualization/exploration.html).


## Key Insights for Presentation

For the presentation, I focused on explanatory charts for the main finding, showing the conclusion was drawn from heatmaps.

In short, the more money you currently make, the more likely it is to get a cheaper loan.

Check out the [HTML slides for Prosper loan analysis here](https://alexmpaz.github.io/data-visualization/slide_deck.slides.html).

## Project Review

This project was graded by a qualified assessor from Udacity and the [resulting report in PDF is here](https://alexmpaz.github.io/data-visualization/project%20review%20by%20Udacity.pdf).
