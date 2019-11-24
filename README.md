# Roomies

Cross-platform hybrid app offering great control and tracking of roommate expenses.

## Backend Needs
Unique-Identifier or 'House Key'. This is the identifier used to reference a household of roommates. There should be table for keys with a one-to-many relationship to user accounts.
User Accounts. Each user account can be associated with a 'House Key'. User accounts will need to store email, password, name, and account type (email, facebook, twitter). Passwords will need encryption. There will need to be a table for user accounts, 
Peer-to-Peer ACH transactions. An API for peer-to-peer transfers will be needed for users to make a payment.
