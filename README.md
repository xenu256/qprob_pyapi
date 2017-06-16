# QProb API (Python version)
[![Build Status](https://travis-ci.org/xenu256/qprob_pyapi.svg?branch=master)](https://travis-ci.org/xenu256/qprob_pyapi)

# Demo(s)

Those will (or already) no longer work under Python. See [qprob_goapi](https://github.com/xenu256/qprob_goapi) instead.

* https://api.qprob.com/ (quantitative trading)
* https://api.stckmrktnws.com (stock market)
* https://api.bsnssnws.com/ (business)
* https://api.entreprnrnws.com/ (entrepreneurship)
* https://api.realestenews.com/ (real estate investing)
* https://parameterless.com/ (technology)

# Technologies

* [Python](https://github.com/python/cpython) 3.6+
* [Sanic](https://github.com/channelcat/sanic)
* [aiomysql](https://github.com/aio-libs/aiomysql)
* Nginx
* MySQL
* [Let's Encrypt](https://letsencrypt.org/)

# How to run

Well, well, first you need the data, generated by [QProb](https://github.com/xenu256/QProb)
(that's the hardest part), use sample [environments file](https://github.com/xenu256/QProb/blob/master/.env.sample)  
from there too. Configure Nginx. And initialize the api_server/api.sh with with Upstart or something else. Easy.
