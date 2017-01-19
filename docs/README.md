# This is a GitHub Pages site

The point of this repository is to offer some in-Apereo-context resources for approaching GitHub Pages, through a lightning talk and supporting materials.

+ [the slides][]

There are two things here in this README.

1. Supporting materials, hyperlinks
2. Meta about [the slide presentation][the slides]

## Resources for understanding GitHub Pages

### Examples in Apereo

+ apereo.github.io blog
+ oaeproject.org
+ early progress on a new uPortal manual

### About GitHub Pages

+ https://pages.github.com/

### About Jekyll

GitHub Pages is a classy, SaaS implementation of the free and open source Jekyll site generator. GitHub is pulling this off with panache, and largely with open source Jekyll and open source plugins for Jekyll.

This means you can run Jekyll locally instead, for development or even for production generation of your website.

### About Static Site Generators

Jekyll is an implementation of the static site generator idea.

There are a slew of static site generators out there besides Jekyll.

You could use any static site generator with GitHub pages hosting, committing the generated site rather than just the source into the GitHub repository for your site. That is, you could still take advantage of the static hosting and much of the Git features, you'd just be losing the convenience of GitHub running the site generator transformation for you.


## The slides

Specifically, it's a web page that implements a Shower slide deck, generated via Jekyller.

### Local usage

Try 

```shell
bundle exec jekyll serve
```

When that doesn't work, dig into Jekyll and Ruby documentation. :shrug:

### GitHub Pages

GitHub pages automatically generates and hosts the static site from this directory. :smile:

[the slides]: https://apetro.github.io/github-pages-lightning-talk/
