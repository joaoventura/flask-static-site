# Flask-static-site

Flask-static-site is a skeleton Python/Flask application ready to be deployed as a static website. You just need to define your own styles, update the content and build the website.

Flask-static-site is released under an MIT Licence.


## Motivation

Building static websites with frameworks such as Flask allows for a clear separation of concerns. For instance, you can separate website functionality over multiple files or use technologies, such as markdown, to generate HTML content. It gives you the benefits of a dynamic framework with the speed of serving static files.

This project is based on [this tutorial by Nicolas Perriault](https://nicolas.perriault.net/code/2012/dead-easy-yet-powerful-static-website-generator-with-flask/). You should try to do it, and maybe check my code for some other ideas.


## Installation

Flask-static-site is a Python 3 application and depends on the **Flask** microframework, **flask_flatpages** to read and parse markdown files from the filesystem and **flask_frozen** to generate static html files for each URL route. Install them with:

> pip3 install -r requirements.txt

To get flask-static-site, you can clone this repository or download a zip file from the right menu.


## Development & Building

Start the development server with `python3 site.py`, open a browser and go to [http://localhost:8000](http://localhost:8000). You should see the skeleton website fully functional.

To add content to the website, open the **pages** folder and check its content. Basically, every website page is a markdown file converted to HTML. In **pages/blog** you will find the blog articles.

In the **static** folder you should put all static files, such as images, css styles and other files. Adapt the css to your own needs.

If you need to change some functionality, check the flask source code at **site.py**. It's the only Python code, and it is very simple to understand once you understand Flask.

Finally, to build the static website, just run `python3 site.py build` in the console. The result will be in **/build**. Upload it to a static webserver and you're done!

