# Egypt 2030 Hackthon


The United Nations Egypt in partnership with the Ministry of Social Solidarity, RiseUp, and PepsiCo are organizing a three-day Hackathon where 21 teams of youth aged between 18-29 will compete to offer innovative digital solutions designed to tackle two of Egypt’s national development priorities and Sustainable Development Goals, Zero Hunger and Gender Equality.

## project include.

- Mobile app for farmer developed using React native.
- Blockchain backend developed using Hyperledger composer for demonstration.
- WP for project workflow.

## TODO
Replace Wordpress web application with Angular app to connect with REST Server generated from blockchain, this would help in traceability for each transaction in the chain.

![REST SERVER](https://github.com/mmjazzar/auction/blob/master/screencapture-159-122-179-126-31099-explorer-2019-04-20-06_03_49.png?raw=true)


## Use cases I worked on


## For Farmers.

### Registration page

Open App
Welcome message from splash screen

![REST SERVER](https://github.com/mmjazzar/auction/blob/master/Login.png)


### Home page Screen

Capture picture and send Voice notes.
Check announcement.

### Messages

Check previous messages.

![REST SERVER](https://github.com/mmjazzar/auction/blob/master/Messages.png)

## For Investors and associaton (UX)

### Registration page

Open App
Welcome message from splash screen
Find deals

Bid item screen

necessary details about item (full detailed name of item and item description)
real-time information about auction (current bid and bidding time duration)
call-to-action to place final bid.

TODO Search by location 

## Blockchain part (Integration)

### Register a user on blcokchain
Register multiple users by clicking on "Create Account".
**user could be investor/farmer 

### Register an Asset
Once the user is registered, they can add an asset by clicking on "Action" -> "Register Asset" Complete the requested fields. Keep in mind the User's Owner Id specified when creating the user account. This will be used for the "Current Owner ID" field.

Once the asset is registered, you can see the asset displayed on the auction homepage.

The asset could be a specific demand (shcool meals) 

### Opening an auction

Click on "Actions" -> "Auctions". You should see the "AUCTIONS" window that will allow you to click on "Open Auction" Enter a duration period in minutes and click on the "OPEN AUCTION" button at the bottom.

### Bid on Asset

Click on "Actions" -> "Bid On Asset". Follow the instructions listed paying attention to the time remaining in the existing auction. Submit Bids with different available user IDs, Highest Bid Price will be updated periodically on UI.Clicking on BuyItNow will close the Auction immediately and no more auctions can be submitted. Once Auction is closed updated details can be seen on Asset Details view.

### Transfer Asset

Click on "Actions" -> "Transfer Asset". An asset can be transferred by entering existing user id and clicking on the Transfer button. Updated details can be seen from Detail View of the Asset.
