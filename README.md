Oolong Times
============

repo of articles - links to great technical reads, blogs,
news, mailing list threads, videos and more

How to contribute?
-----------------
#### Installation
- Jekyll
[Install Jekyll with gems](http://jekyllrb.com/docs/installation/)
- Octopress
[Install Octopress](https://github.com/octopress/octopress)
<code>$ gem install octopress --pre</code>

#### Dependencies
- Once you clone the project, you may update the dependencies by
<code>$ bundle install</code>

#### Adding new content
- Create an article by 
 <code>$ octopress new post "New Post Title" --dir articles</code>
- Goto _posts/articles/<your_new_post> and do all the writeup required.

#### Testing and Deploying
- Comment 'url' part  in _config.yml to run it on localhost
- Run <code>$jekyll serve --baseurl "" -w</code>
- Open the browser and hit [Oolong Times](http://localhost:4000/)
- When all is well, you may push the changes :)

License
-------
No copyright intended
