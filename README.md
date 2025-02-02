![Ws-4](https://github.com/user-attachments/assets/0c01dbed-5db6-45e4-abb3-cb03de548a6e)
# Web-Scrapping 
#### It is the process of extracting data from websites using code. It allows you to gather information from webpages by downloading the HTML content and parsing it to extract the desired data.
#### Python offers several libraries to help with web scraping, the most popular ones being:
 Requests: Used to send HTTP requests to retrieve the HTML content of a webpage.<br/><br/>
 BeautifulSoup: A library for parsing HTML or XML content and navigating the structure to extract useful information.<br/><br/>
 Selenium: Often used for scraping dynamic content, where JavaScript is involved in rendering data.<br/><br/>
 lxml: A library that is also used for parsing HTML and XML content, known for its performance and ease of use.

#### Basic Steps for Web Scraping:
  1). Send a Request to the Website: Use requests or Selenium to retrieve the HTML page.<br/><br/>
  2). Parse the HTML: Use BeautifulSoup or lxml to parse the page.<br/><br/>
  3). Extract the Data: Find the specific elements on the page using HTML tags, classes, or IDs, and extract the data.<br/><br/>
  4). Save the Data: Store the scraped data in a file, such as CSV, or a database.

#### Example with BeautifulSoup and requests:
![image](https://github.com/user-attachments/assets/3ba77003-e792-491c-a0d6-52a4f7dad216)

#### In my case i am navigating the Flipkart website and searching the items by Rice Cooker:
![WS_SS](https://github.com/user-attachments/assets/b6fdb4d6-eba8-48cd-8508-55035b63eb26)

#### Using Webscrapping we collect data insights from flipkart website, and export it into CSV files, and transforming it into insightful Pandas DataFrames.
#### Here’s a step-by-step breakdown of our code:
  
  #### 1. Import essential libraries:
  
  ![image](https://github.com/user-attachments/assets/1dc9f93b-208e-4309-8328-205e1ae8d1d0)
  
  #### 2. requests for fetching web content
  
  ![image](https://github.com/user-attachments/assets/3cecd9c6-0d8c-4611-8b73-885d451b10a0)
  
  #### 3. BeautifulSoup for parsing and extract the details from the html elements
  
  ![image](https://github.com/user-attachments/assets/6c37161e-38f0-4464-a9db-239626d01fe7)

  #### 4. Using the browser's "Inspect Element" feature, we navigate to the relevant "div" section and extract the necessary details of the required elements.
 
  ![Screenshot 2025-02-02 161147](https://github.com/user-attachments/assets/81514a56-9008-4b64-94ca-3993a7e9ae87)

  #### 5. Pandas for data analysis 
  
  ![image](https://github.com/user-attachments/assets/bada579e-1822-484d-9ca5-25c3627659ea)

  #### 6. Finally exporting the data to csv
  ![image](https://github.com/user-attachments/assets/3ee46300-dc41-42bf-a0ba-4a8b0c515584)

  ![image](https://github.com/user-attachments/assets/b2f3703f-effc-4eea-baa0-3cf984b94e7e)


