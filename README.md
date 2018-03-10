# CAR18 Chicago
## Introduction to Web Scraping

adapted from Alex Richards' ([@alexrichards](https://www.twitter.com/alexrichards)) excellent [IRE17 class](https://github.com/richardsalex/ire17-python2).

He'll also be teaching a repeat web scraping session [Sunday](https://ire.org/events-and-training/event/3189/3709/)!

### This session will cover:


- How web scraping will make your life easier
- How to do so responsibly
- Using third-party Python packages
- Fetching web pages with Python
- Navigating the HTML in those pages to get data
- Structuring scraped data and writing it to a CSV
- And a couple of tips on shortcuts with HTML tables!

### Software requirements:

You should have Python on your machine. Type the following in Bash (on Mac OS, you can access it with an Application called Terminal) to check that you have the correct version for the class:

```bash
which python3
```

which should return something like

```bash
/Library/Frameworks/Python.framework/Versions/3.5/bin/python3
```

If not, and you're in the CAR18 class, you should flag down the instructor or a TA. If you're not in the class, [download Python3](https://www.python.org/downloads/).


If you already have Python 3, you should be able to run the command `pip install -r requirements.txt` after downloading this repository to get the packages listed below:

- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/)
- [Jupyter](http://jupyter.org/)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/)
- [requests](http://docs.python-requests.org/en/master/)

### Have questions?

You can always:

- [Send Alex a note](mailto:arichards@nerdwallet.com) (arichards@nerdwallet.com)
- [DM Alex on Twitter](https://www.twitter.com/alexrichards)
- [Reach out to Melissa](http://melidata.com/contact)
- open an issue here

**Struggling with installation?** Try this [updated guide](https://gist.github.com/richardsalex/abc3d36cc128a37f650c1fc3c9cb04a2) for Windows and OS X.

### Resources:

#### Python

- [PyCAR](https://github.com/ireapps/pycar) for in-depth Python learning
- [CodeAcademy](https://www.codecademy.com/learn/python) for Python syntax
- [Think Python](http://greenteapress.com/wp/think-python-2e/), a popular introductory book whose digital edition is available free online

#### Scraping

- The Coursera class [Using Python to Access Web Data](https://www.coursera.org/learn/python-network-data), for which you may want to take preceding classes in preparation

#### The Internet

- [How the Internet Works](http://pyvideo.org/pycon-us-2013/how-the-internet-works.html), a PyCon 2013 talk by Jessica McKellar
- [How Does The Internet](https://shop.bubblesort.io/products/how-does-the-internet-zine), a zine as informative as it is cute, by Amy Wibowo
