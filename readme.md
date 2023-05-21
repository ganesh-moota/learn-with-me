### Project Structure

```
.
├── _includes
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   └── 1970-01-01-placeholder-post.md
├── .gitignore
├── README.md
├── _config.yml
└── index.html
```

### _config.yml

This is where you will be putting your Jekyll configuration options. If this
file is omitted Jekyll will use its defualts to build your site. You can find
the configuration options and default configuration
[here](https://github.com/mojombo/jekyll/wiki/configuration).

### _layouts

This folder is where all the layout templates are stored.

#### default.html

This is the base layout template. There are no naming conventions, but if you
choose to change this file's name make sure you update all the layout
references in your file's YAML Front Matter blocks. To learn more about the use
of YAML Front Matter check out [this
page](https://github.com/mojombo/jekyll/wiki/yaml-front-matter).

#### post.html

This is the base post template.

### _posts

This folder is where all the posts are stored. Notice the naming convention
that is used. You will want to name your files with the the publish date
preceeding the posts title all seperated by dashes
(Year-Month-Day-Title-Of-The-Post.md). The post date that you see is pulled
straight from this filename so make sure you lable your files right.