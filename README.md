# klajdi-bregu
git clone https://github.com/username/username.github.io
cd username.github.io
echo "Hello World" > index.html
git add --all
git commit -m "Initial commit"
git push
git clone https://github.com/username/username.github.io
cd username.github.io
git checkout publish
git branch -m master
git push -u origin master 
git branch -D gh-pages
git push origin --delete gh-pages
git branch -d gh-pages
---
title: "home"
bg: white     #defined in _config.yml, can use html color like '#010101'
color: black  #text color
style: center
---

# Example headline!
and so on..
---
title: "Art"
bg: turquoise  #defined in _config.yml, can use html color like '#0fbfcf'
color: white   #text color
fa-icon: paint-brush
---

#### A new section- oh the humanity!
sudo apt-get install ruby ruby-dev build-essential nodejs
sudo gem install github-pages
git push -u origin master
