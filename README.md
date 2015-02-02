# pelican-bootstrap3-fabacademy

This is the theme I've made for my [Fab Academy 2015 site](http://fabacademy.org/archives/2015/eu/students/chalmers.iain/index.html).
It's based on the [pelican-bootstrap3](https://github.com/DandyDev/pelican-bootstrap3) theme by [Daan Debie](https://github.com/DandyDev).

## Installation

First:

`git clone https://github.com/icchalmers/pelican-bootstrap3-fabacademy.git`

Then:

Point the `THEME` variable in your `pelicanconf.py` to `/path/to/pelican-bootstrap3-fabacademy`

## Usage

Most of the usage remains the same as for the base pelican-bootstrap theme, although in my hammering of the code I've probably broken some features...

Some features that I know no longer work:

* Due to limits on the generated site size for Fab Academy, I've removed all of the [Bootswatch](http://bootswatch.com/) themes except for 'flatly'.

* I've added some CSS for controlling the navigation sidebar in 'static/css/pelican-bootstrap3-fabacademy.css', so make sure add the following line to your pelican config file:

```
CUSTOM_CSS = 'static/css/pelican-bootstrap3-fabacademy.css'
```
