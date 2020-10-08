# A1: Data Curation 

## 1. Project Goal 
The goal is to pull data from a publicly available source, be able to use data processing techniques to clean the data and use the final product to pinpoint a trend in some feature of the data, in this case activity in the form of traffic on the English Wikipedia ( mobile and desktop ).

## 2. Project License 
This project is under the MIT License. View the [License file](/LICENSE.md) for more information.

## 3. Data Source 
The Wikimedia Foundation REST API has provided this information, on their older Pagecounts or Legacy API and their newer PageViews API. Documentation on the API can be found on [Wikimedia's website](https://wikimedia.org/api/rest_v1/). 
Refer to the [terms and conditions](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions) before use.

## 4. Fields in the final file.
The final csv file will contain monthly traffic counts related to the following categories.:
  - Timestamp
  - Pageviews data(total)
  - Pagecount data (total)
  - Pageviews data for mobile
  - Pageviews data for desktop
  - Pagecount data for mobile
  - Pagecount data for desktop.
  
## 5. Additional info
There is an unequal amount of information for different fields, for example mobile data is harder to find before October of 2014. The Pageviews API also includes data from mobile-apps and mobile-websites, which can be combined. In addition data in the Pageview API excludes crawlers while the Pagecounts API does not. 
  
