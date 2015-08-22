title: FLASK-STATIC-SITE
image: /static/images/pier_bw.jpg


# A brief background

Flask-static-site is a skeleton Python/Flask application ready to be deployed as a static website. You just need to define your own styles, update the content and build the website.

Building static websites with frameworks such as Flask allows for a clear separation of concerns. For instance, you can separate website functionality over multiple files or use technologies, such as markdown, to generate HTML content. It gives you the benefits of a dynamic framework with the speed of serving static files.

<div class="center isolated">
    <a class="button" href="{{ url_for("page", path="about") }}">ABOUT FLASK-SKELETON</a>
</div>

---


# HTML in markdown files

You can add html code in markdown files. The buttons and this image are HTML.

<div class="blog-image">
    <img style="width:100%;" src="/static/images/lake3_branding.jpg" />
    <p>I could work everyday in a place like this..</p>
</div>

---


# Ipsum lorem

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nec leo diam. Donec porta, sem quis semper dictum, sem ex pharetra nulla, vitae tristique turpis urna vel augue. In justo dolor, tincidunt ut nibh vel, eleifend aliquet metus. Duis nisl augue, vehicula quis vehicula at, dictum at diam. Aliquam ante purus, ornare nec leo nec, dignissim porttitor turpis. Integer urna odio, venenatis vitae leo eget, sollicitudin scelerisque ante. Vestibulum commodo id quam id dapibus. In non mauris at libero egestas posuere accumsan vitae est. Phasellus turpis urna, rhoncus id volutpat tempor, pulvinar condimentum justo. Nulla cursus ante sed urna sollicitudin dapibus non dapibus odio. Sed vel mollis velit. Nulla mauris turpis, gravida non ultrices in, placerat et odio.

Aenean id tincidunt velit. Integer nec ligula eu turpis bibendum consequat ac a ligula. In pharetra, elit et semper lacinia, diam arcu pharetra arcu, sed sollicitudin est erat vitae sem. Aliquam sed urna nulla. Praesent volutpat risus iaculis purus dignissim tincidunt. Phasellus semper tellus ut dictum egestas. Phasellus quis pretium eros. Pellentesque consequat enim vitae luctus feugiat. Aliquam ut porttitor sem, eu tincidunt sapien. Proin gravida erat sed eros condimentum rutrum. Etiam et pulvinar velit.

---


<!-- Button -->

<div class="center isolated">
    <a class="button" href="{{ url_for("page", path="contacts") }}">CONTACT</a>
</div>
