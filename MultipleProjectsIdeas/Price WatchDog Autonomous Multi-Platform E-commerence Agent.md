# Price WatchDog Autonomous Mutli-Platform Ecommerence Agent

( Artificial Intelligence / Web Programming / Web Automation )

## IDEA

User provide us input of single product name, single product url to our llm checks that the page is up means webpage is live not server crashed down then it uses playwright to extracts the sementics of webpage while ignoring sidebars and other prices sidebars if the product is out of Stock then he say the product is not available, if there are different variants of product like SSD 256 price and 128 then it will give user different options about which product do you want to select and then he extract the product name, price and currency. and uses library like turndown to convert the messy html to markdown for LLM and then the price drops like 500 and it generate notification to your email using tools like nodemailer and storing CSV file for saving the history

## Questions :

- What is like standard scrapping scripts that that breaks when UI changes while scrapping data from websites.
- How agent can watch the live semantics of website for product name, price, currency
- How can do web scrapping without blocked by priceOye or draza
- which model we are going to use for training of reAct( Reasoning and action) of product.
- Is we should set the price parameter or if the small amount of price drops of product then the notification is triggers.
- There are multiple extensions out there like keepa that are available for price tracking how do you define your project is different from them

## Solutions

1. Like your ip address is blocked by website while doing scrapping
2. we use library playwrite built by microsoft for reading the page source or reading the semantics.
3. I don't we use different methods
4. Free tier of gemni or chatgpt
5. The targeted price is set by user that if the price drops below 1800 then the message or notification is send to user let's suppose the price of ram is 2000 and we set first that if the price is less than 1800 message us
