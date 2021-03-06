---
author: Peter Baumgartner
category: Sponsorship
date: 2018-10-03 08:00:00
layout: post
image: /static/img/blog/ll_logo_landscape_color.svg
title: "Lincoln Loop: The Interesting and Underrated Parts of Django"
---

Hi everyone! This is Peter Baumgartner, founder at [Lincoln Loop](https://lincolnloop.com), with a sponsor guest post. This is our 9th year sponsoring the conference. A look back at [the talk schedule from 2009](https://web.archive.org/web/20091214145046/http://www.djangocon.org:80/2009/conference/schedule/) shows we were just starting to talk about using git and GitHub (at the time, subversion and Google Code were the norm) and Ian Bicking was introducing pip and virtualenv. Despite the technological sea change that has happened since then (mobile, PaaS, containers, etc.), Django is still as relevant as ever, powering some of the biggest sites and apps online.

Even though Django is no longer the shiny new up-and-comer, we still have the same joy of working with it on a daily basis. Most of our developers have been using Django for over a decade and can provide some unique perspective on the project. We thought it might be interesting to ask a few of them what they are most interested in right now and what part of Django they think is the most underrated.

### [Peter Baumgartner](https://lincolnloop.com/team/peter-baumgartner/)

#### Interested In: [`pyuwsgi`](https://pypi.org/project/pyuwsgi/)

uWSGI is _the_ choice for people who want to get the most performance out of their Django sites. Unfortunately, the packaging of the project left a little to be desired. Recently, Lincoln Loop sponsored development to improve the Python packaging of uWSGI and publish pre-compiled wheels to PyPI. This means you can now install uWSGI quickly with no additional development tools and run it as a management command with [`django-pyuwsgi`](https://pypi.org/project/django-pyuwsgi/). That all unlocks some interesting new possibilities which I'll discuss in my presentation, [Containerless Django](https://2018.djangocon.us/talk/containerless-django-deploying-without/).

#### Underrated: [`ManifestStaticFilesStorage`](https://docs.djangoproject.com/en/2.1/ref/contrib/staticfiles/#manifeststaticfilesstorage)

I've seen all sorts of home-grown ways for handling static file versioning to improve performance with far-future expiration dates, but this one built into Django since 1.7 can be enabled with a single line in your settings.

### [Chris Beaven](https://lincolnloop.com/team/chris-beaven/)

#### Interested In: [Channels](https://github.com/django/channels)

Django channels is often pigeon-holed as "websockets for Django". While it is a good tool for that, I'm more interested in the discussions it leads into around the possibilities of adding more asynchronicity to the Django stack. Having full ansychronous capabilities in Django opens the door to a lot of new options for us as developers.

#### Underrated: The Community!

Both Djangonauts and the wider Python community aim to be inclusive and welcoming to people of all skill sets. From a code perspective, I would say we take for granted the number of well supported third party packages developed and maintained by the community.


### [Brian Luft](https://lincolnloop.com/team/brian-luft/)

#### Interested In: Python 3 Evolution

With the big Python 2/3 schism behind us, I'm excited to see what comes of some of the Python 3 features like `asyncio`. Tom Christie's new API framework [API Star](https://docs.apistar.com/) is reimagining Python on the web and Andrew Godwin's work towards an [asynchronous Django](https://www.aeracode.org/2018/06/04/django-async-roadmap/) should be interesting.

#### Underrated: Stability

We've grown accustomed to an endless upgrade cycle in modern web development. Thankfully, Django is one piece of software that doesn't follow that pattern. Being able to pin your backend to an LTS version and know you won't need to perform any major upgrades there for a couple years is great for stability. It lets businesses focus on building features instead of spinning the upgrade hamster wheel.

### [Martin Mahner](https://lincolnloop.com/team/martin-mahner/)

#### Interested In: [Internationalization](https://docs.djangoproject.com/en/2.1/topics/i18n/)

For many of the projects we work on, serving content in multiple languages is a key requirement. Delivering a great workflow around adding translations is a challenge and there isn't a one-size-fits-all solution. Typically we're building something not only for the primary content managers, but also externally contracted translators and/or third-party services.

#### Underrated: [URL Dispatcher](https://docs.djangoproject.com/en/2.1/topics/http/urls/)

URLs are the key component to connecting your code to the outside world. People take it for granted how good we have it in the Django world. Django's `urlpatterns` are an elegant and easy-to-use solution to the problem.

---

We'd love to hear your thoughts as well. Stop by our booth at the conference to talk shop or ask questions with some of our team. See you in San Diego!
