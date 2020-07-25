Merge Pipfile
==============

A development tool for joining pipenv dependecies to join source code packages into a single project.

Merges the Pipfiles in the current directory with any other Pipfiles in sub-directories.

Used as a tool to allow for unpublished custom libraries to be included in your virtual environment made by Pipfile

**Note**
Currently, the search for pipfiles starts in the current directory and searches sub-directories recursively.

Installation
------------

Install using pip

`pip install pipfilemerge`

If using Pip Env

`pipenv shell`
`pip install --dev pipfilemerge`

Usage
------

`python -m pipfilemerge`

Or within a script

`import pipfilemerge`

`pipfilemerge.update()`
