# Tweet-Scraping
SELENIUM

Selenium WebDriver allows you to choose a programming language to create test scripts. As discussed earlier, it is an advancement over Selenium RC to overcome a few limitations. Selenium WebDriver is not capable of handling window components, but this drawback can be overcome by using tools like Sikuli, Auto IT, etc.

XPATH

Xpath (XML Path Language) is a query language for selecting nodes from an XML document. In addition, Xpath may be used to compute values (e.g., strings, numbers, or Boolean values) from the content of an XML document. Xpath was defined by the World Wide Web Consortium.

IMPLEMENTATION

1.	In order to do scraping, first we need to automate the browser, to do so we have used Selenium web-driver. Here, we first import all the required libraries. Then we create an instance of web-driver by downloading it and then by giving the path of it in the code. Before downloading the webdriver we have to check the version of it as well as the browser. In our case, we are using Google Chrome we downloaded chromedriver.exe, if it was firefox driver, we would have downloaded the geckodriver and in case of mircosoft edge browser, we would have downloaded the msedge driver As we are scraping twitter, we have used the .get() function. 

2.	As we are interested in twitter handle, username, postdate, text of the tweet, reply count, retweet count and like count, we have taken the Xpath of all these and written them in function. We have used error handling in timestamp because there are some tweets which are sponsored, and these tweets do not show timestamp i.e., the time at which is tweet is posted. All these are included in the tuple and then the tuple is returned.

3.	After all the required data is scraped, we have stored in a .csv file. So first we created a .csv file and by using the functions in file handling all the scraped data has been filled in it.



