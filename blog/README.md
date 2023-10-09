# ossboard

``` 
jekyll new io
cd io
#npm install
bundle exec jekyll serve

bundle exec jekyll build
rsync -avh --delete _site/* ../ossboard.github.io/blog/
cd ../ossboard.github.io
git add *
git commit -m "blog"
git push origin main
cd ../io

```