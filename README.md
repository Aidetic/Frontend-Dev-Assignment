# Data-Science-Assignment

# Test Details:
  This test was created by Aidetic Software Pvt. Ltd. for Frontend Dev Hiring. Anyone can take this test.
  
  Instructions:
  
    1. Fork this repository.
    
    2. Write your code and commit it to your personal fork.
    
    3. Important: Keep you fork private and share it with the following Email IDs:
    
            a) abhishek@aidetic.in
            
            b) yadvendra@aidetic.in
            
            c) ketan@aidetic.in
            
            d) mehul@aidetic.in
            
    4. Fill this form: https://forms.gle/jW6eW7zrcengT3gW7
    
    5. Once you have submitted the form someone from our time will reach out to you for the next steps.

# Overview:
  The goal of this assignment is to develop a small application for news analytics.

# What will the application look like and what will it do?

  The requirement is to develop a news analytics dashbaord which will fetch you some analytics given some search keywords. The Application will have three user roles: Admin, Standard User and Premium User. 

  # Pages:
    
      Front Page: With a drop down to choose from 'Admin', 'User' and 'Premium User'.

      Normal User Home Page: 2 Block on the home page. "Word Frequency Analysis" and "Source Analysis" 
      
      Premium User Home Page: A 3 * 3 grid with 9 Block. "Word Frequency Analysis", "Source Analysis", Remaining 7 can be named "Dummy Analysis"
      
      Admin Home Page: Empty page with the header saying Admin page. (Dummy Page)
      
      Analytics Page: Page with a header saying the analysis name and a search bar. Upon searching any term it will fetch and display the requested analytics.

      404 Page: All bad routes(which you have not implemented) will lead to this page.
    
   # Routing Information:
      
      Front Page: /
      
      Normal User Home Page: /normal-home
      
      Premium User Home Page: /premium-home
      
      Admin Home Page: /admin-home
      
      Analytics Page: /analytics
      
      404 Page: /not-found
      
        * Create more routes as per the requirements and name them sensibly.
   
   # Application Flow:
    
      1. User will choose the role on the front page.
      2. Based on the role, user will land on the correct home page. 
      3. On the premium and standard home page user should be able to click the requested analytics.
      4. Upon selecting the requested analytics, user will be redirected to analytics page.
      5. Analytics page will show "Word Frequency Analysis" or "Source Analysis" or "Dummy Analysis" depending on which block did you click on home page.
      6. Upon searching any term an API will be called to fetch data, details for the API can be found below.
      7. Using the fetched data, you have to render a graph based on the analysis requested. Graph details can be found below.
      
      
   # API to Call:
      You can create a free account here: https://newsapi.org/ and use the same for fetching news articles.
      
   # Graphs Required:
      
      Word Frequency Analysis: Sorted column chart of Unique Words vs Number of Occurence of word across all articles. https://www.highcharts.com/docs/chart-and-series-types/column-chart
      
      Source Analysis: Column chart of News Source vs Number of Articles. https://www.highcharts.com/docs/chart-and-series-types/column-chart
      
      Dummy Analysis: Word Cloud with Random Data. https://www.highcharts.com/docs/chart-and-series-types/word-cloud-series
      
   
# Deliverables
  
  1. The final deliverable is a GitHub repository containing all files for running the application. 
  
      ○ src folder with all the components and services. 
      
      ○ package.json with all the required dependencies.
      
      ○ Any static image file you decide to use.
      
      ○ A folder with the screenshot of all the pages.
      
      
  2. Application requirements:
   
      ○ User of a particular role should not be able to access the home page of other roles.
      
      ○ User should not be able to access the home page without choosing the role.
      
      ○ When a new search query is entered the graph should update without the need of refreshing the page.
      
      
  3. Coding Instructions and General Guidelines:

      
      ○ Write docstrings for your methods.
      
      ○ Format the code properly using a formatter in your IDE.
      
      ○ Assign variable names intelligibly.
      
      ○ Reuse your components as much as possible.
      

All the best and do reach out in case you have any questions. Cheers!
