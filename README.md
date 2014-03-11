Overview
    MRISA (Meta Reverse Image Search Api) is a RESTful api which takes a url, does a reverse image search and returns a json array with standard search information such as title, description, destination url and the total number of search results.

Releae Notes
    0.1 - returns json encoded array with

Python Dependancies
    for systems using apt:
        apt-get install  python-flask python-pycurl python-beautifulsoup

    If you are using pip, the following command should get you going:
        pip install flask pycurl beautifulsoup simplejson

Running
    Just a case of running the following command in the project root directory
    python server/mrisa_server.py
