# Pinax

[![Join us on Slack](http://slack.pinaxproject.com/badge.svg)](http://slack.pinaxproject.com/)

Pinax is an open-source platform built on the Django Web Framework. It is an ecosystem of reusable Django apps, themes, and starter project templates.
This collection can be found at http://pinaxproject.com.

Getting Started
------------

To give you an example of how one would use Pinax now to start a new
site based on the Account Starter Project follow these steps in your shell:

```
pip install virtualenv
virtualenv mysiteenv
source mysiteenv/bin/activate
pip install pinax-cli
pinax start account mysite
cd mysite
pip install -r requirements.txt
./manage.py migrate
./manage.py loaddata sites
./manage.py runserver
```

Documentation
--------------

The Pinax documentation is available at http://pinaxproject.com/pinax/. If you would like to help us improve our documentation or write more documentation, please join our Slack channel and let us know!


Contribute
----------------

See our [How to Contribute](http://pinaxproject.com/pinax/how_to_contribute/) section for an overview on how contributing to Pinax works. For concrete contribution ideas, please see our [Ways to Contribute/What We Need Help With](http://pinaxproject.com/pinax/ways_to_contribute/) section.

In case of any questions, we would recommend for you to [join our Pinax Slack team](http://slack.pinaxproject.com) and ping us there instead of creating an issue on GitHub. Creating issues on GitHub is of course also valid but we are usually able to help you faster if you ping us in Slack.

We would also highly recommend for your to read our [Open Source and Self-Care blog post](http://blog.pinaxproject.com/2016/01/19/open-source-and-self-care/).  


Updating Docs
-------------

The docs live online at http://pinaxproject.com/pinax/. You can update them by
running:

```
mkdocs gh-deploy
```



Code of Conduct
-----------------

In order to foster a kind, inclusive, and harassment-free community, the Pinax Project has a Code of Conduct, which can be found here  http://pinaxproject.com/pinax/code_of_conduct/.


Pinax Project Blog and Twitter
-------------------------------

For updates and news regarding the Pinax Project, please follow us on Twitter at [@pinaxproject](https://twitter.com/pinaxproject) and check out our blog http://blog.pinaxproject.com.

