# UNSW Vovinam Site (http://unswvovinam.org)

## Intro
This repo contains the source code used for a simple static website http://unswvovinam.org. This site is my gift to my martial arts club at my university.

The webpage is hosted as a [Github page](https://pages.github.com/) and hence
it uses [Jekyll](https://jekyllrb.com/). I also use [Muffin](http://richbray.me/muffin/) to simplify the design of the page. I would like to thank the Jekyll community and @richardbray for their work. 

## Installation

### Setup
1. Clone this project: `git clone https://github.com/tvhong/vovinam_site.git`
2. Follow instructions on this [Github help page](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) to install Ruby and the Rubygems required for the project. Note all the required RubyGems for Jekyll and Muffin are already set in the project's `Gemfile`.

### Running local server

1. Go to your repo, run `sh watch.sh`. This shell script will check and compile `*.scss` files to `*.css` if needed.
2. Bring up Jekyll server by `bundle exec jekyll serve --baseurl ""`. The baseurl option there is to override baseurl option in _config.yml in case you have any.
3. Visit http://localhost:4000/ in your browser and your page is there.If that doesn't work, check your terminal output for the `Server address` link.

## Make it your own
Although I don't see why you may want to fork from this project but in case you do, you could check out the "Getting Started" section on [Jekyll's documentation](https://jekyllrb.com/docs/) (note you have already finished the installation part). Also check out SCSS and Muffin documentation to see what they have to offer.

Tip: You might want to start by changing the settings in `_config.yml`
