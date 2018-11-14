# Web Scraping
* Talk by [Adi Eyal](https://github.com/adieyal)
* He is a data scientist for `code4sa` and has done a lot of public work with scraping.

> You have a question, you can use scraping to get the answer
# Technical
Tips
* Captcha
    * Can stop your scraper, but if its badly setup - not entirely
* VPN
    * If you are scraping a website, and you break it
    * It could technically be a Denial of Service (DOS) attack
    * Best to be safe
* Slow Scraping
    * If you scrape too fast you can kill the site
* Crawling
    * Downloading all the data
* Chrome / Headless
* PDF
* Mobile version
    * Can sometimes be better to scrape
* Search
    * An empty search box may result in all the possible queries
* Legalities
    * Check their terms of use on the website
    * Government sites can be rather dangerous to scrape, especially if you DOS them by them
    * If you scrape a site on AWS, it might increase their bill for increased usage - which they could claim back for you
* ID Numbers
## Simple
For some simple ones, you can basically do this
* Use google sheets, import table
* `=importhtml`
## Capitec
Another basic example
* Capitec ATM locations
* Going through a list of ATMS and scraping data
* [capitec ATMS](/capitec_atms)

## Kwazulu Natal Law Society
Scraping becomes more difficult if you are looking at multiple pages. So you have a list of pages and details within that list
* This example goes through pages
* [Law Society](/lawsoc)


# Morph IO
Useful tool for seeing previous *scrapers* code
# Tabula
A tool that allows you to collect data from PDFs
* Amazing for getting tables 

# Examples
## Medicine
* Original data for medicine prices here
    * [mpr.gov.za](http://mpr.gov.za/)
* Created a better representation, where you can find generics and the price you can pay
    * [https://mpr.code4sa.org/](https://mpr.code4sa.org/)

## Politicians
* Municipal elections data
* A list of ID numbers for election candidates
* Analysis of the data
    * Age 
    * Gender
* Based on one additional piece of information, the outcome of the election, can deduce gender biases

## Property Evaluations
* All online
* Can find out valuation of properties
* https://www.capetown.gov.za/Family%20and%20home/Residential-property-and-houses/Private-properties

## Health Professional of South Africa
http://www.hpcsa.co.za/