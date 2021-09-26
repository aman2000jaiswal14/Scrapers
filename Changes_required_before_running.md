# Ajio_Scraper

- (First time change only) Change the start and prev id next_allot_index
- Change to root_path in utils/write_data_utils.py, utils/prev_index_utils.py file to the current directory of Ajio_Scraper
- Change the sys.dir path in spider/scraper.py file to the current directory of utils file

# Myntra_Scraper
- Similar to Ajio


# Limeroad_Scraper
- Replace the base_url in the scrapper.py file with the current category/subcategory url which need to be scraped.
- Rename the category variable for which category its belong(Wome,Men,Kids)
- Change the TotalPages variable and PriceFilters according the subcategory(Western/tops) it want to scraped. 

# Myntra_Review_Scraper
- Put the scraped CSV file in the spider folder

# Myntra_Suggestion Scraper
- Put Suggestion Label excel sheet( Label_ref_v1.xlsx) in the spider folder


# Nykaa_Scraper
- No changes

# Flipkart_Scraper
- Make filters file like Brand, Color, Style etc, and put it into the Spider/FilterFoder
- write the script for added filters in the FlipkartFilters.py file
- import that filter function in the scrapper.py file

