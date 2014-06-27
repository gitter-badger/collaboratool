Python dependencies
-------------------

### Ubuntu packages

rabbitvcs pulls in Ubuntu ipython which we displace later with pip

### Python packages

**< = requires package ; > = pulls in**

 - boilerpipe < default-jre default-jdk
 - boilerpipe > JPype1 charade
 - rpy2 < liblzma-dev
 - pyyaml < libyaml-dev
 - pandas > dateutil pytz numpy
 - ipython > tornado pyparsing nose backports.ssl-match-hostname
 - sphinx > Pygments docutils Jinja2 markupsafe
 - scrapy > Twisted w3lib queuelib cssselect
 - scrapy < libxslt1-dev libssl-dev
 - flask > Werkzeug itsdangerous
 - ipythonblocks < ez_setup
 - seaborn < patsy
 - seaborn > husl moss statsmodels
 - ipython notebook < pyzmq libzmq3-dev
 - *apt-get installing python-gtk2-dev is much faster than pip-installing gtk2*

