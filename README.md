# Clean Blog for Middleman

This is my conversion of the [Clean Blog](https://startbootstrap.com/template-overviews/clean-blog/) template to [Middleman](http://middlemanapp.com).  
There are [many](https://github.com/sandiegoscott/middleman-clean-blog) versions [like it](https://github.com/Devahoy/middlehoy), but this one is mine.  
My code is ugly. It is not pro-level by any stretch. I will master it as I master my ruby skills.  


The things I've modified or added:  
* English Ordinal dates (e.g. May 1st, 2016, June 11th, 2017 rather than May 1, June 11... ) (*requires 'facets' gem*)
* `vendor` removed and everything smashed in to `assets`  
* Google Analytics
* Social & sharing buttons for each post (facebook, twitter, reddit, email)
* Meta tags for Open Graph  
* Various configurable settings via `data/site.yml`  
   * siteurl (*mostly for proper social sharing links and OG data*)  
   * sitename (*ditto*)  
   * subtitle  (*just because*)  
   * author  (*easier than going through the templates to replace each instance*)  
   * google_tracking_id (*comment out and it won't be included in the partial*)  
   * twitter (*footer*)  
   * facebook (*footer*)    
   * github (*footer*)     

Feel free to fork and modify it to suit your own site needs/improve my awful code.  

See it in action [here](http://lunestaconfessions.com)



# Original README:  
# [Start Bootstrap](http://startbootstrap.com/) - [Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/)

[Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/) is a stylish, responsive blog theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features a blog homepage, about page, contact page, and an example post page along with a working PHP contact form.

## Getting Started

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](http://startbootstrap.com/template-overviews/clean-blog/)
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-clean-blog.git`
* Fork the repo

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-clean-blog/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/clean-blog/).

## Creator

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2016 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-clean-blog/blob/gh-pages/LICENSE) license.