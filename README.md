# blog.trigger-happy.eu
Blog of the project Trigger Happy.

Follow it to get the news.

## Installation

```shell
virtualenv blog.trigger-happy.eu
cd $_
source bin/activated
git clone https://github.com/push-things/blog.trigger-happy.eu
git clone --recursive https://github.com/getpelican/pelican-plugins
mv blog.trigger-happy.eu website
pip install -r requirements.txt
pelican-theme -s $PWD/pelican-bootstrap3
```

## Ready to create blog post ;)

For that, [go to that link](https://github.com/push-things/blog.trigger-happy.eu/new/master) and enjoy a new post ;)


## Theme pelican-bootstrap3

this one provide tipue_search plugin but this one provide a version of Tipue which is outdated (version 4) and buggy.
version 5 works fine. To install it, just clone https://github.com/Tipue/Tipue-Search, remove from website/output/theme/tipuesearch and, in place of this one,add the tipuesearch coming from the clone you just made.
