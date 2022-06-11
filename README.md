# Welcome to Stock scraping api!

Hi 👋🏻!  I'm developing an api for stock scan screen using web scraping.

**Current state** ⛏ in progress 


# Stack

 - Node
 - Express
 - Playwright
 - JWT
 - MongoDB

# Data stocks source

I am using **[Finviz](https://finviz.com)** to scan stock with following ipo base filter:

 - **Market Capital** *under $ 10Billion*.
 - **Average Volumne** *Over 200K*.
 - **IPO Date** *In the last 5 years*.
 - **Prive** *Over $7*
 - **Sales growth qrt over qrt** *Over 20%*.
 - **52-Week High/Low** *0-10% below high*.
