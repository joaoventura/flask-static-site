title: Some instructions
date: 2015-04-23
published: true
image: /static/blog/2015/branding_blank_ad.jpg
summary: Welcome to the blog section of flask-static-site. To add a blog article just create a file in pages/blog/year and fill the following details. (...)


Welcome to the blog section of flask-static-site. To add a blog article just create a file in pages/blog/year and fill the following details.

* **title**: the title of the blog.
* **date**: date of the publication.
* **published**: if true, the article will appear in the blog index page.
* **image**: background image for the article.
* **summary**: a brief summary to be displayed in the blog index page.

There is a **static/blog** folder, you should drop all blog related files (images or other) in that folder.

The blog index page will only include the 3 latest blog articles. If you want to change that number, or include all articles, just update the following function in **site.py**.

    :::python
    @app.route('/blog/')
    def blog():
        articles = get_blog_articles(reverse=True)[:3]
        return render_template('blog/index.html', pages=articles)

Enjoy it!
