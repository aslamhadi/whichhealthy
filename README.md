Whichhealthy
============

Content and design for http://whichhealthy.com/.

## Setting up:

* Setup pip, virtualenv, and virtualenvwrapper. [link](https://jamie.curle.io/posts/installing-pip-virtualenv-and-virtualenvwrapper-on-os-x/)

* Once you activate the virtualenv, run `pip install -r requirements.txt`

## Testing locally

After add/edit content, run `make html` and `make serve`. And then go to http://localhost:8000 to see the web locally.

## Publishing

Make sure you have configured `s3cmd`. After that, run `make s3_upload` to publish to the web.

## Note

If you are interested in writing in the blog, feel free to send an email to wahidyankf@gmail.com or aslamhadi@gmail.com
