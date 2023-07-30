# scrape-linkedin-to-report
Scraping a company's linked in page, collecting posts content and posts analytics using Beautifoul Soup and Selenium.


### What does this script do?
- This is a complete notebook that can automatically scrape **Linked In** profiles of companies, and export the information as a word document.
- It requires a linked in account so that the program can login to linked in and move around freely. For optimal results, using the same web browser as your webdriver (in my case Chrome) log in to the linked in account you are going to use. This ensures that no 2-factor authentication is asked when scraping automatically, and will greatly reduce time especially if you are planning to bulk scrape multiple companies.
- The only input necessary is a company's main profile page url.

  
### Setup
The main 2 packages used are Beautiful Soup and Selenium. In addition, a webdriver is needed, in this case *webdriver.Chrome()* is used. This essentially creates an instance of Google Chrome which selenium can control. 

To install the Chrome driver, follow this link (https://chromedriver.storage.googleapis.com/index.html?path=114.0.5735.90/). Once the file is downloaded, **add the executable file** to a folder already on the path, or save it to another folder, and add that to the path.
