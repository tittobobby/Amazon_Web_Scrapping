# Amazon_Web_Scrapping

This repository aims to document the web scrapping process of the price of Redmi Note 11 mobile phone from Amazon.in

URL used : "https://www.amazon.in/gp/product/B09QS9CWLV/ref=s9_acss_bw_cg_Budget_6a1_w?pf_rd_m=A1K21FY43GMZF8&pf_rd_s=merchandised-search-7&pf_rd_r=TBD15D57H8XPWMBC049A&pf_rd_t=101&pf_rd_p=854f427d-8d08-4cdf-a7c3-190fea343a08&pf_rd_i=1389401031&th=1"

This script that scrapes data from the Amazon website for a specific product (Redmi Note 11) and writes the product title, price, and date to a CSV file named "AmazonWebDataSet.csv". The script also includes a function called "check_price()" which does the same scraping process and is meant to be run periodically to check if the price of the product has changed.
The above script is written in python and is using the BeautifulSoup, requests, smtplib, time, datetime, csv, and pandas libraries.
