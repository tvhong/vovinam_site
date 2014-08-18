UNSW Vovinam Site
=================
I developed a site for my martial art club at UNSW using Jekyll with [Muffin](http://richbray.me/muffin/) template. 

I can't remember the detail installation. You will need to first fork the repo, then clone it using `git clone ssh_link_to_this_repo`. Install dependencies & Jekyll following [this Github instruction](https://help.github.com/articles/using-jekyll-with-pages).

By this time you should have got Ruby installed. And rubygems as well.

Now, comes the fun part: Run your server :)
1. First, run `sh /path/to/repo/watch.sh` in a terminal. This shell script checks and compiles `*.scss` files to `*.css` if needed.
2. Then, bring up Jekyll test server by running the command `bundle exec jekyll serve` (as per the instruction on the Github page).
3. Visit http://localhost:4000/ or anything that you see in "Server address" from the previous command

And _hopefully_ everything will work.
