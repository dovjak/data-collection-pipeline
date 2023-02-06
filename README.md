# Data Collection Pipeline

This project will be focused on scraping the using BeautifulSoup and Selenium Webdriver. 

## Milestone 1

Here the Github was set up

## Milestomne 2

In this milestone I have chosen to scrape the reviews from trustpilot.com and different features related to the review. This is because scraping this website has got a lot of space to improve the complexity of the project. Initially, the data is being scraped for 'Booking.com', but a user could be allowed to interact with it and insert their own company to scrape the reviews from, but in this case more methos would be needed to overcome dropdown options, because after entering the company in the search box and clicking 'Enter', for some companies it goes straight to the revies and for others giving to choose the company from the list which requires extra actions. In addition, having the automated reviews scraping could be really helpful for the business to improve their services.

## Milestone 3

The Scraper_Class has been created with the main inititializers and the methods to navigate the page were written. 
Methods to navigate the page: 
Methods to scrape the features of the reviews:

After all this, the code is run using if \__\name\__\=="__main__" to ensure that the code is run directly and not being imported. Success.

## Milestone 4

More methods were created. These methods involve: next_page_button() - to move onto a next page, extract_pages_number() - to extract the maximum number we can loop over the pages, read_data_for_more_pages() - this method links the methods of clicking the next page button and scraping the features of the reviews as well as adding them to the lists of thse features of previous pages, map_data_into_dictionary() - to map feature values to feature names, save_review_data() - to save data dictionaries in json format.
Need to comment on those why I need them.
