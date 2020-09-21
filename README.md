# Introduction

Hello and welcome to the frontend assignment for Bitvavo in this assignment you will be creating a simple cryptocurrency top 10 list with a few small features. 
This test is primarily to test your ability to set up and start working on something in Vue with Typescript. You will be using some very basic wireframing images to guide your design of the interface, though styling-wise it's up to you to be creative.

# Technologies

The following technologies must be used:

- Vue 2+
- Typescript
- SCSS
- Jest

Other than the above your more than welcome to use anything that you think might make this task simpler, better or more production ready.

# Submission Requirements

This assignment should take no longer than 4 hours, though feel free to take a little longer if it's required. If you're uncertain about anything during the assignment let us know, and we can try to provide some guidance.

1) Firstly you should fork or clone this repository to your own account and all work should be done alongside the files here (were expecting to see a professional commit history). 
2) The code that you submit should be considered production ready, submissions which keep this in mind often come across better.
3) Try to follow the screens provided and provide us with a solution that has clearly followed the brief visually.
4) Optional features are optional, if you don't have time do not include them. It's better to make a submission that doesn't have half baked work.
5) Try to avoid using `any` for your typescript definitions, we expect to see properly constructed type safety.
6) The final solution must work and run, please provide setup instructions if it's not already clear how to run the code.

We have provided some extra space below the assignment under `notes` here if you'd like to you can make some notes about the assignment or any of the decisions you made.

Finally, once you think you've finished the assignment please send a link to a publicly accessible repository, so our team is able to take a look over the code.

# Assignment

To create your top 10 crypto currency tracking dashboard you will be using the CoinMarketCap api which you can find here: https://coinmarketcap.com/api
 and specifically you'll be interfacing with assets which are found here: https://coinmarketcap.com/api/documentation/v1/#operation/getV1CryptocurrencyListingsLatest
 
You will need to signup for an api key and it will need to be used for all of your requests, if you have any issues integrating with this api let us know and we should be able to help.

All the corresponding screen wireframes have been made available inside this repository and are name the same as the sub-headings below

### Screen 1:

Screen 1 is the main homepage screen and should be accessible under the `/` and `/home` Navigation paths, it requires the following functionality:

1) It lists the current top 10 most traded currency
2) Each currency should have the following columns in order: Rank, Name, Symbol, Price, Market Cap and Change 24h
3) Clicking on the `Name` field should direct users to screen 2
4) It shows the bitvavo logo in the logo area

Optional:

Asset Images (Bitcoin logo etc)
In Table sorting on columns
Paging or Infinite scroll that allows us to go beyond the top 10 currencies
Search Field which allows you to search for any crypto currency in the API
Night/Light Mode which restyles the app globally


### Screen 2:   

1) It lists all the previously shown information about the asset
2) It shows the quote information for BTC to USD
3) Allows users to navigate back to the homepage

Optional:

Users can choose to open another panel which shows the same information listed above but for a different currency than the one already selected

Please provide any tests you think are appropriate alongside the final submission, though they are optional.

# Notes
