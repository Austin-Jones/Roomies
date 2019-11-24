# Roomies

Cross-platform hybrid app offering great control and tracking of roommate expenses.

## Backend Needs

#### Unique-Identifier or 'House Key'
This is the identifier used to reference a household of roommates. There should be a table for keys with a one-to-many relationship to user accounts.
#### User Accounts
Each user account can be associated with a 'House Key'. User accounts will need to store email, password, name, and account type (email, facebook, twitter). Passwords will need encryption. There will need to be a table for user accounts.
#### Household Info
There will need to be a table for household info. This table will have a relationship to user accounts and house key tables. Entries include: Number of roommates in household, what roommates are using the app, what percentage 
#### Expenses
There will need to be a table for expenses that has a relationship to 'house key' and user account tables. This table will track each expense, and include an identifier to create a relationship between each expense and 'house key', and date the expense is due.
#### Expense percentage
This a table that will hold the percentage of an expense a roommate needs to pay. This will have a relationship to user accounts and expenses
#### Peer-to-Peer ACH transactions 
An API for peer-to-peer transfers will be needed for users to make a payment.
