# Amazon-Web-Scraper 🛒📄
![amazon-logo](https://user-images.githubusercontent.com/93293695/184787302-1d133c5e-9869-4df5-b667-e016cb7e308b.png)

## Summary:
Basic Amazon web scraping script using selenium. This version runs with a firefox browser. 
The script opens up the browser and amazon.ca. The script will then run a search based on the provided keyword (Its set to seearch for "Best Seller")  and then downloads: 
----
Product Name 
----
Unique ID 
----
Price 
----
Rating 
----
Number of Ratings 
----
Product Link 
----
Image 
----
Image Link 
----

into a spreadsheet. 

## Driver:
To change driver please download one of the following:  
Chrome: https://chromedriver.chromium.org/downloads  
Edge: https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/  
Safari: https://developer.apple.com/documentation/webkit/testing_with_webdriver_in_safari 

## Configure:  
Change the following lines to your webdriver of choice:
```python
driver = webdriver.Firefox()
```
```python
driver = webdriver.Chrome()
```
```python
driver = webdriver.DriverOfChoice()

## Please note that the search results as is may provide adult content. 
