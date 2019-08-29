# https://smithara.github.io

Based on the jekyll-clean theme: https://github.com/scotte/jekyll-clean

To run it locally:
```
sudo apt install ruby ruby-dev rubygems nodejs
sudo gem install jekyll jekyll-paginate

git clone https://github.com/smithara/smithara.github.io.git
cd smithara.github.io
jekyll serve --baseurl=''
```
Now browse to http://127.0.0.1:4000


To add a new post: just add a new .md file in `./_posts`

To add a new page, make a new .html or .md file in project root. Add the entry to `./_includes/header.html`
