SpiderFoot is an open source footprinting tool, created by Steve Micallef <steve@binarypool.com>. It is designed to be easy to use, fast and extensible.

Visit the project website at http://www.spiderfoot.net.


Downloading
--

To get the packaged and tested SpiderFoot releases for your platform:
https://sourceforge.net/projects/spiderfoot/files

To get the latest source and tinker around with it yourself:
https://github.com/smicallef/spiderfoot


Unix
--

This fork of Spiderfoot works under Python 3

To install the dependencies using PIP (https://pypi.python.org/pypi/pip), do the following:

```bash
$ pip install cherrypy
$ pip install mako
```

To run SpiderFoot, simply execute sf.py from the directory you extracted SpiderFoot into:

```bash
$ python ./sf.py
```

Once executed, a web-server will be started, which by default will listen on 0.0.0.0:5001. You can then use the web-browser of your choice by browsing to http://127.0.0.1:5001. 

If you wish to make SpiderFoot accessible from just this system:

```bash
$ python ./sf.py 127.0.0.1:5001
```

If port 5001 is used by another application on your system, you can change the port:

```bash
$ python ./sf.py 127.0.0.1:9999
```


Bugs
--

All bugs are tracked in github, please visit: https://github.com/smicallef/spiderfoot/issues for spiderfoot in particular; at least until python3 is accep


Feature Request
--

A UserVoice instance has been set up for capturing feature requests, please visit: http://spiderfoot.uservoice.com to request new features or vote on other people's requests.

