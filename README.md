UNSW Vovinam Site
=================
This is the source code for UNSW Vovinam site. It is hosted as a Github project page. It uses Jekyll and [Muffin](http://richbray.me/muffin/) template. 

First, you'll need to install Ruby, Rubygems(included in Ruby). Then install
bundler gem to help manage the dependencies of your gem in this repo. Then use
bundler to install other gems required for this repo. All of that are written
here:
[Github](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll).

Note that I already populated the Gemfile in the repo so you don't need to do
that.

To run your server, follow these steps:

1.Go to your repo, run `sh watch.sh`. This shell script checks and compiles `*.scss` files to `*.css` if needed.

2. Then, bring up Jekyll server by `bundle exec jekyll serve --baseurl ""`.
   The baseurl setting is there because my site is a Github project page as
   oppose to a personal Github page.
   See http://jekyllrb.com/docs/github-pages/ for more details.

3. Visit http://localhost:4000/ in your browser and you'll see your page there.
   If that doesn't work, use the link in your "Server address" output from the previous command instead.

You may need to change baseurl setting in \_config.yml to match your page structure. See http://jekyllrb.com/docs/github-pages/
