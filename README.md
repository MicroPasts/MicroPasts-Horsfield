PyBossa photo tagging application
=================================

[![DOI](https://www.zenodo.org/badge/20326003.svg)](https://www.zenodo.org/badge/latestdoi/20326003)

This application has three files:

*  createTasks.py: for creating the application in PyBossa, and fill it with some tasks.
*  template.html: the view for every task and deal with the data of the answers.
*  tutorial.html: a simple tutorial for the volunteers.

![alt screenshot](https://farm3.staticflickr.com/2918/14443363844_d99632eb9b.jpg)

Testing the application
=======================

You need to install the pybossa-client first (use a virtualenv):

```bash
    $ pip install pybossa-client
```
Then, you can follow the next steps:

*  Create an account in PyBossa
*  Copy under your account profile your API-KEY
*  Run python createTasks.py -u http://crowdcrafting.org -k API-KEY
*  Open with your browser the Applications section and choose the FlickrPerson app. This will open the presenter for this demo application.

Documentation
=============

We recommend that you read the section: [Build with PyBossa](http://docs.pybossa.com/en/latest/build_with_pybossa.html) and follow the [step by step tutorial](http://docs.pybossa.com/en/latest/user/tutorial.html).

**NOTE**: This application uses the [pybossa-client](https://pypi.python.org/pypi/pybossa-client) in order to simplify the development of the application and its usage. Check the [documentation](http://pythonhosted.org/pybossa-client/).


LICENSE
=======

Please, see the COPYING file.
