# Final Project CS509 Fall24- Auction House

DEMO - https://vimeo.com/1042981102?share=copy

## Lisp Team: 
  -Sharvi Nitin Ghogale
  
  -Rohan Rana
  
  -Brian Rojas
  
  -Antonela Tamagnini

## Getting Started

Clone the repository with: `[git clone https://github.com/yourusername/auction-house.git](https://github.com/brianEtrials/team-bars-lisp-auction-house.git)`. You’ll be on the main branch by default.

## Installing modules for `main`

To properly install everything, do the following:

```bash
npm install
npm install react@18 react-dom@18
npm install react-router-dom
npm install react-secure-storage
npm install bootstrap
```

Then to launch, type:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the Auction House interface.

### Iteration 1: Use Cases (10)

  Buyer:
  
    -Create Account

    -Login to Account

    -Add Funds

  Seller:
  
    -Create Account

    -Login to Account

    -Add Item

    -Review Items

    -Remove Item

    -Publish Item

    -Unpublish Item

### Iteration 2: Use Cases (10)

  Buyer:
  
    -Close Account

    -View Item

  Seller:
  
    -Close Account
    
    -Request Unfreeze Item
    
    -Archive Item

  Customer:
  
    -Search/Filter Items

    -Sort Items

    -View Item

  Admin:
  
    -Freeze Item

    -Unfreeze Item
    
### Iteration 3: Use Cases (10)

  Buyer:
  
    -Search recently sold

    -Sort recently sold

    -Place bid 

    -Review active bids of buyer 

    -Review purchases 

    -Buy Now (new use case) 

  Seller:
  
    -Edit Item
    
    -Fulfill item

  Admin:
  
    -Generate Auction Report

    -Generate Forensics Report

#### Landing Page: http://auctionlisp.s3-website-us-east-1.amazonaws.com

### Info for use cases testing:

- Credentials for login buyer: username:testbuyer, password:test
- Credentials for login seller: username:testseller, password:test
- Credentials for login admin: username:admin, password:admin24 (login inside 'Sign in' page)
- Item Name should always be unique.
- Price Range: enter i.e. 'price 1 to 10' in the search field.
- When a buyer purchases an item, they are redirected to the home page. If they place a bid, they remain on the same page but cannot bid again to outbid themselves.
- When an item is purchased using the Buy Now option, the transaction is completed, and no other buyers can purchase it, even if the end date has not yet passed.

# Auction House Screenshots:

## Landing Page - Customer Page

<img src="auction_website/customer_page.png" alt="Example Image" width="500">

<img src="auction_website/customer_view_item.png" alt="Example Image" width="500">

<img src="auction_website/login_create_account.png" alt="Example Image" width="500">

  
## Admin Side

<img src="auction_website/admin_dashboard.png" alt="Example Image" width="500">

<img src="auction_website/admin_freeze_unfreeze_item.png" alt="Example Image" width="500">

<img src="auction_website/admin_auction_report.png" alt="Example Image" width="500">

<img src="auction_website/admin_forensic_report.png" alt="Example Image" width="500">


## Seller Side

<img src="auction_website/seller_1.png" alt="Example Image" width="500">

<img src="auction_website/seller_2.png" alt="Example Image" width="500">


## Buyer Side

<img src="auction_website/buyer_view_active_items.png" alt="Example Image" width="500">

<img src="auction_website/buyer_view_sold_items.png" alt="Example Image" width="500">

<img src="auction_website/buyer_auction_item.png" alt="Example Image" width="500">

<img src="auction_website/buyer_buy_now_item.png" alt="Example Image" width="500">

<img src="auction_website/buyer_profile1.png" alt="Example Image" width="500">

<img src="auction_website/buyer_profile2.png" alt="Example Image" width="500">









