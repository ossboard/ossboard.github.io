# ossboard

``` 
jekyll new io
cd io
#npm install
bundle exec jekyll serve

bundle exec jekyll build
rsync -avh _site/* ../ossboard.github.io/blog/
cd ../ossboard.github.io/blog/
git add *
git commit -m "blog"
git remote -v
git push origin main
cd ../io
```