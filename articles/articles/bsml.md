bsml Setup Guide (incomplete)
jeff
2023-03-03
page.html
link
bsml is a simple static blog generator using just one shell script.  
With a couple of markdown files and determination, you can set up an easy-to-update blog.  
If you're looking for an example of a site built with bsml, look no further! This entire website runs on bsml and the template files are available [here!](https://github.com/parlajatwit/bsml-template)
# Prerequisites
- Linux environment (or anything capable of running sh files)
- Web Server for hosting (I recommend GitHub pages since it's free)
- Markdown knowledge
# Setup
If this is your first time setting up bsml, you should clone the [template repository](https://github.com/parlajatwit/bsml-template)  
Inside, there are a few template files (index.html, page.html, category.html, no\_meta.html)  
You can use these later for setting up general pages.  
index.html redirects your index page to go to the build pages.  
page.html is a generic page, featuring an article title, author, date, and content, along with more articles in said category at the bottom.  
category.html is a category page. This holds links to all of the articles in the category and allows you to add an overview of the category.  
no\_meta.html has no metadata, just an article title and content. 
