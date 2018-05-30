# Simple Jekyll
barebones Jekyll website framework

### Demo
![Jekyll Demo](/assets/images/jekyll-demo.png)

### Files
- `_config.yml` the default settings for your site as well as various global parameters you can set
- `_includes` elements of web pages such as headers and footers that you can "include" on any page, post, or layout
- `_layouts` are templates to reuse as much code as possible for pages, posts, and whatever other type of web pages you would like
- `_pages` is a folder I always make to store pages, it is not a standard part of the jekyll skeleton
- `_posts` is the folder containing all the website posts in the proper format, makes blogging a breeze
- `_site` is the folder jekyll makes when run that contains the static html/css site after jekyll pre-processing has been done
- `assets` is a folder I make to house the sass/css, images, fonts, documents and javascript for the site
- `favicon.ico` is the small icon that appears at the top of the browswer
- `index.html` the default landing page for your site, gets updated by jekyll and put in the `_site` folder after elements are processed

### Getting Started
1. Install Jekyll on your host machine
2. Clone the repo or download and extract the zip file
3. Navigate to the repo in command line and run `jekyll serve` to start jekyll and create a locally hosted webserver
4. Open your web browswer and navigate to `localhost:4000` to see your site
5. To stop Jekyll, run `Ctrl + C` in the command line
