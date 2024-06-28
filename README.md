# tumblr_blog_scraper
Code to scrape the content from my erasmus blog

# Usage
- this is only for personal usage, to save your own content, not to be used for other purposes

1. Go to the archive view of your page
  the url should look like something like this: 
  https://username.tumblr.com/archive
2. Download this page - it is going to create a folder and a .html file
3. Copy the path of the .html file to the _tumblr_archive_html_ variable 
  it is at the first cell of the Execute section
4. Run all

# Output: 
- a csv file containing:
  - title of the post
  - url of the post
  - date of the post
  - text of the post
  - hastags of the post
- a json file with the same content as the csv
- all the pictures from each post, where the naming will follow the below format:
  - {title}_{number}.jpg --> post_about_somethig_1.jpg
  - currently it outputs the files to the same directory where the code runs
