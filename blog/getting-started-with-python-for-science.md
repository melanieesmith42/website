---
title: "Recommended reading to get started with Python for science and data analysis"
date: 2017-02-07
thumbnail: getting-started-python.png
layout: post
---

I get asked a lot in the [Fatiando a Terra][/software/fatiando]
[mailing list](https://groups.google.com/d/forum/fatiando)
how to do some basic Python and numpy tasks which are not necessarily related
to Fatiando.
The most common question is some variant of "I have some data in a csv/txt/xyz
file and I want to load it into Python".
I think this happens because a lot of people find the project while searching
for a replacement for GUI based commercial projects,
like Geosoft's Oasis Montaj,
but they don't necessarily know Python.
So instead of writing yet another email,
I decided to ["Reply to public"](http://matt.might.net/articles/how-to-blog-as-an-academic/)
here.

Here are my recommendations (in order):

0. **Don't start** with a general Python programming book/site/tutorial/video.
   They are usually meant for programmers, not scientists. You'll have to wade
   through mountains of string formatting and Fibonacci numbers before you find
   an answer to "How do I load these data?" (and it won't be `numpy.loadtxt`).
1. Start with the [Software Carpentry
   lessons](https://software-carpentry.org/lessons/). Read all of them if you
   can. **Everything there will make your life easier.** If you don't have the
   time, focus on "Programming with Python" and "Version Control with git".
   The lessons are **not** detailed but instead show you what is out
   there and what you should type into Google.
2. After you wet your appetite, **dive deeper** into more detailed material. I
   highly recommend the [Scipy Lecture Notes](http://www.scipy-lectures.org/).
   If you like the feeling of paper in your hands and have some money to spare,
   try the books
   [Effective Computation in Physics](http://shop.oreilly.com/product/0636920033424.do)
   by [Anthony Scopatz](http://www.scopatz.com/) and
   [Katy Huff](http://katyhuff.github.io/)
   and [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do)
   by [Jake VanderPlas](http://staff.washington.edu/jakevdp/).
   **Beware that I have not read these books** so I cannot vouch for them
   (but I have read good reviews online).
3. Now that you have the basics down, **use the project documentation pages**
   to find specific instructions for what you want, for example the
   [numpy documentation](http://www.numpy.org/) and the
   [matplotlib gallery](http://matplotlib.org/gallery.html).

From now on, learning new things will be a continuous process. I've been
programming Python for 10 years and every once in a while I'll still learn
something new, usually that reduces the amount of code I have to write (less
code = less bugs).
The key is to stay informed and you can do that by subscribing to some (or all)
of the following:

* [Planet Scipy](https://planet.scipy.org/), an aggregator feed for scientific
  Python blogs.
* The [Python Weekly](http://www.pythonweekly.com/) email news letter.
* The podcasts [Podcast.\_\_init\_\_](https://www.podcastinit.com/) and
  [Talk Python To Me](https://talkpython.fm/). See my [previous post for more
  podcast recommendations][/blog/podcasts-2016].

Now go out there and learn a skill that just might save you in these times of
crisis!

*How did you get started with Python? Do you have anything to add to this list?
Let me know!*

---

*The open science logo is by [G.emmerich on Wikimedia
Commons](https://commons.wikimedia.org/wiki/File:Open_Science_Logo.jpg)
and the picture of the Python book is by
[Marcus Brown](https://www.flickr.com/photos/marcusjhbrown/14939378037).
Because both are licensed CC-BY-SA, then so is the thumbnail image for this
blog post (a composite of the two images).*