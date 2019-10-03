# Modelling Credit Risk
## Introduction
   In this project I will focus on credit modelling, a well known data science problem that focuses on modeling a borrower's credit risk. I'll be working with financial lending data from Lending Club. Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.

### Project Scope
While Lending Club has to be extremely savvy and rigorous with their credit modelling, investors on Lending Club need to be equally as savvy about determining which loans are more likely to be paid off. Most investors use a portfolio strategy to invest small amounts in many loans, with healthy mixes of low, medium, and interest loans. In this project, I'll focus on the mindset of a conservative investor who only wants to invest in the loans that have a good chance of being paid off on time. To do that, I'll need to first understand the features in the dataset and then experiment with building machine learning models that reliably predict if a loan will be paid off or not.

## Problem Statement
Can I build a machine learning model that can accurately predict if a borrower will pay off their loan on time or not?

## Data
Lending Club releases data for all of the approved and declined loan applications periodically on [their website](https://www.lendingclub.com/info/statistics.action). The data dictionary can be found [here](https://docs.google.com/spreadsheets/d/191B2yJ4H1ZPXq0_ByhUgWMFZOYem5jFz0Y3by_7YBY4/edit).

The `LoanStats` sheet describes the approved loans datasets and the `RejectStats` describes the rejected loans datasets. Since rejected applications don't appear on the Lending Club marketplace and aren't available for investment, I'll be focusing on data on approved loans only. The approved loans datasets contain information on current loans, completed loans, and defaulted loans.

I'll be focusing on approved loan data from 2007-2011 since most of the loans during this period have already been resolved. More recent datasets contain too many loans that are still in the process of being paid off.
