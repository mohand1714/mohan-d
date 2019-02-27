# mohan-d
## Task 1 - Monefy

Hi,

I have arranged the testing approach based on the core functionality of the app starting with any CRUD operation, followed by visual representation of the chart in homescreen and the settings page. I have just given the basic coverage and not the brief test cases.

Notation| Priority
------------ | -------------
P0| High
P1| Medium
P2| Low



**App Launch**

Areas to test| Priority
------------ | -------------
User should be able to launch the app after a fresh installation | P0
User should be able to launch the app after an app update | P0

**Adding an expense/income entry from -/+ icon**

Areas to test| Priority
------------ | -------------
User should be able to Add an Income entry by tapping on + icon | P0
User should be able to Add an Expense entry by tapping on the - icon| P0
User should be able to add a note while making a expense/income entry | P2

**Balance page**

Areas to test| Priority
------------ | -------------
User should be able to see the balance in the Balance button | P1
User should be able to see the transactions in a new page when tapped on Balance button  | P0
User should be able to Add an Income entry from the Balance page | P0
User should be able to Add an Expense entry from the Balance page | P0


**Homescreen transaction chart**

Areas to test| Priority
------------ | -------------
User should be able to Add an Expense entry by tapping on a category icon from the homescreen | P0
User should be able to see the Expense entry in the home screen | P0
User should be able to see the Income entry in the home screen | P0
User should be able to see the Transfer entry in the home screen | P0
User should be able to see chart update with the icon when a expense entry is made | P1
User should be able to see chart update with the icon when a Income entry is made | P1
User should be able to see the overall transaction sum in the center | P2
User should be able to see any eidt/delete to an transaction updated in the chart | P1

**Editing an expense/income entry**

Areas to test| Priority
------------ | -------------
User should be able to update an Income entry (USD, Note, Category) | P0
User should be able to update an Expense entry (USD, Note, Category) | P0
User should be able to update an Trasfer entry (USD, Note, Category) | P0
User should be able to Delete an Income entry (USD, Note, Category) | P0
User should be able to Delete an Expense entry (USD, Note, Category) | P0
User should be able to Delete an Trasfer entry (USD, Note, Category) | P0


**Accounts Interaction**

Areas to test| Priority
------------ | -------------
User should be able to add multiple accounts from the accounts pane | P0
User should be able to see the newly added account in the left pane | P0
User should be able to see the toggle between multiple accounts in the left pane | P1
Transactions made in Account A should not be reflected in Account B and vice-versa | P0
User should be able to see the home screen change according to the account selected | P0


**Money Transfer**

Areas to test| Priority
------------ | -------------
User should be able to transfer money from Account A to Account B | P0


**Transaction display based on timeline**

Areas to test| Priority
------------ | -------------
User should be able to see the transaction based on the timeline selected  - Day/Week/Month/Year/All/Choose Date  | P1

**Categories**

Areas to test| Priority
------------ | -------------
User should be able to add custom categories | P1
User should be able to edit (change name/icon) existing categories | P1
User should be able to delete categories | P1


**Currencies**

Areas to test| Priority
------------ | -------------
User should be able to but the Pro version of the app | P0


**Settings**

Areas to test| Priority
------------ | -------------
User should be able to modify the General settings in Settings pane | P1
User should be able to sync the data in 3P apps ( Google drive/Drop box) | P2
User should be able to create backup/restore/delete data | P0
