# GitHub Pages Lightning Talk

The point of this repository is to offer some in-Apereo-context resources for approaching GitHub Pages, through a lightning talk and supporting materials.

+ [the slides][]

There are two things here in this README.

1. Supporting materials, hyperlinks
2. Meta about [the slide presentation][the slides]

## Resources for understanding GitHub Pages

### Examples in Apereo

+ [apereo.github.io blog][] ([source][apereo.github.io source])
+ [oaeproject.org][] ([source][oaeproject.org source])
+ early progress on a [new uPortal manual][] ([source][new uPortal manual source])

### About GitHub Pages

+ https://pages.github.com/

### About Jekyll

GitHub Pages is a classy, SaaS implementation of the free and open source Jekyll site generator. GitHub is pulling this off with panache, and largely with open source Jekyll and open source plugins for Jekyll.

This means you can run Jekyll locally instead, for development or even for production generation of your website.

### About Static Site Generators

Jekyll is an implementation of the static site generator idea.

There are a slew of static site generators out there besides Jekyll.

You could use any static site generator with GitHub pages hosting, committing the generated site rather than just the source into the GitHub repository for your site. That is, you could still take advantage of the static hosting and much of the Git features, you'd just be losing the convenience of GitHub running the site generator transformation for you.


## The slide deck

The slide dock is in `/docs`. It's implemented in the Shower open source HTML/CSS/JS slide presentation framework, builds via Jekyller, and actually builds and deploys through GitHub Pages running Jekyll to build and deploy the `/docs` directory as a static website.

If I knew what I was doing with Git I'd incorporate `shower` and the `ribbon` theme by reference rather than by copy, but I don't, so this repo simply has a copy of what it needs from those.

## Supporting documentation

The slides include a few speaker notes.

[the slides]: https://apetro.github.io/github-pages-lightning-talk/

[apereo.github.io blog]: https://apereo.github.io/
[apereo.github.io source]: https://github.com/apereo/apereo.github.io

[oaeproject.org]: http://oaeproject.org/
[oaeproject.org source]: https://github.com/oaeproject/oaeproject.github.io

[new uPortal manual]: https://jasig.github.io/
[new uPortal manual source]: https://github.com/Jasig/uPortal/tree/master/docs
