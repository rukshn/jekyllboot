Jekyllboot - Simple Jekyll Blogging Theme
==

Jekyllboot is a simple blogging theme made for bloggers using Jekyll, the theme is designed using [Bootstrap 3][1]. Also I've added some extras like RSS feed and a blog archive. I first designed this for my blog and you can see a live demo there at [hi.rukshanr.com][2]

Because it's made using Bootstrap it has all the good features of bootstrap, like being mobile first and full responsiveness. 

To use this Jekyll theme, first clone the repo 

    git clone https://github.com/rukshn/jekyllboot

After that change the settings of `_config.yml` file, change blog name description, url twitter username, and everything to your liking.

    
    markdown: redcarpet
    pygments: true
    
    name: "Blog Name"
    tagline : "Anything less than imortality is a complete waste of time"
    description: "Blog Description"
    paginate: 10
    permalink: pretty
    url: "Blog URL"
    author: "Author"
    twitter: "twitter username"

Then open the CNAME file if you are hosting your blog on GitHub pages and clear the file and put your domain name you're going to use, after editing it should look like this,

    example.com

Then open the css folder and upload a header image for your blog, make sure it's large and rename it to `header.png`

Edit the `about.md` file and put a description of yourself.

That's it. Happy blogging, don't forget to star fork and make changes. License [MIT][3]


  [1]: http://getbootstrap.com
  [2]: http://hi.rukshanr.com
  [3]: LICENSE.md
