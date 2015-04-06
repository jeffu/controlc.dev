ControlC.fm
=========

Source repository for ControlC.fm, built with jekyll.


## Building your own copy

It's pretty easy to build a copy of this site. We used [jekyll](http://jekyllrb.com/) which is a ruby program that compiles markdown files into static HTML documents which makes it super easy to put on the web.
Make sure you have ruby installed, then:

1. clone this repo

   `git clone https://github.com/Cbeck527/controlc.fm`

2. cd into the folder

    `cd controlc.fm`

3. install tools and dependencies

    `bundle install`

4. Build the site

   `jekyll build`

You'll have a new folder in the directory called `_site` that has all of the compiled HTML files ready to be thrown at a web server. Pretty nifty!

## Deployment

For deploying to S3, we use a tool called `s3_website` which looks at a file named `s3_website.yml` for configuration information. Take a look at the example file, add your S3 API keys and bucket name and save the file as `s3_website.yml`

Then:

1. configure your bucket

    `s3_website cfg apply`

2. push the code!

    `s3_website push`

## Feedback

Feel free to hit us up on twitter with any questions! [@ControlCfm](https://twitter.com/ControlCfm)
