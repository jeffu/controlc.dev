ControlC.fm
=========

Source repository for ControlC.fm, built with jekyll.


## Building your own copy

It's pretty easy to build a copy of this site. We used [jekyll](http://jekyllrb.com/) which is a ruby program that compiles markdown files into static HTML documents which makes it super easy to put on the web.

Make sure you have ruby/jekyll installed by doing `gem install jekyll`

1. clone this repo

   `git clone https://github.com/Cbeck527/controlc.fm`
   
2. cd into the folder

    `cd controlc.fm`
    
3. Build the site

   `jekyll build`
   
You'll have a new folder in the directory called `_site` that has all of the compiled HTML files ready to be thrown at a web server. Pretty nifty!

## Deployment Playbook

This repository comes with an ansible deployment playbook that automates the compilation and uploading... give it a try!

Feel free to hit me up on twitter with any questions: [@ControlCfm](https://twitter.com/ControlCfm)
