# Professional website for Danielle Ribeiro

* * *

Table of Contents
-----------------
*   [Deployment](#deployment)
*   [Posts](#posts)
*   [Google Analytics](#GoogleAnalytics)

* * *

### Features

* 100% responsive and clean theme

* Optimized for mobile devices

* Minimal design

* Valid HTML5 code

* Post sharing

* Supports Disqus Comments

* Supports Google Analytics

* Google Fonts


* * *

### Deployment

To run the theme locally, navigate to the theme directory and run `bundle install` to install the dependencies, then run `jekyll serve` or `bundle exec jekyll serve` to start the Jekyll server.

I would recommend checking the [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

* * *

### Posts

To create a new post, you can create a new markdown file inside the \_posts directory by following the [recommended file structure](https://jekyllrb.com/docs/posts/#creating-post-files).

      ---
      layout: post
      title: "Welcome to Jekyll!"
      date: 2018-05-29 18:05:55 +0300
      image: '/assets/img/03.jpg'
      tags: Life
      ---


You can set the tags and the post image.

Add post images to **/assets/img/** directory.

For tags, try to not add space between two words, for example, `Ruby on Rails`, could be something like (`ruby-on-rails`, `Ruby_on_Rails`, or `Ruby-on-Rails`).

* * *

### Google Analytics

To integrate Google Analytics, open `_config.yml`, and add your Google Analytics identifier.

    # Google Analytics
    google-analytics: # Add your identifier. For example UA-99631805-1
