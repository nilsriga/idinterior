idinterior.lv

To start install
ruby
bundler
jekyll

to make a production build run
JEKYLL_ENV=production jekyll build --trace

and for development run 
bundler exec jekyll serve


to allow your user to push to server
$ git config core.sharedRepository "all"
$ git config receive.denyNonFastForwards True