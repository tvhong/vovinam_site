UNSW Vovinam Site
=================
I developed a site for my martial art club at UNSW using Jekyll with [Muffin](http://richbray.me/muffin/) template. 

I can't remember the detail installation. You will need to first fork the repo, then clone it using `git clone ssh_link_to_this_repo`. Install Jekyll following [this Github instruction](https://help.github.com/articles/using-jekyll-with-pages).

By this time you should have got Ruby installed. And rubygems as well.

You will need to install `sass` to compile the scss files provided by Muffin (and edited by me). You can install this by running `sudo gem install sass` (I copied that from Google).

Now, the real stuffs happen.
To run the page, first you have to compile `*.scss` files to `*.css` by running `sh /path/to/repo/watch.sh`.
Then you can run Jekyll test server by running `bundel exec jekyll serve` like the instruction on Github page.

And hopefully everything will work.

(Notice that I use a lot of "probably", "hopefully", and other undeterministic words. But anyway, I got my program works. _Hopefully_ yours will work too!
