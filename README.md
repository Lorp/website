## This is a test repo so I can play around with Jekyll (such repos must be public!)

You can use the [editor on GitHub](https://github.com/Lorp/website/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Typefaces

<ul>
  
  
  {% for post in site.categories.typeface %}
    <li>
      <h2><a href="website{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

