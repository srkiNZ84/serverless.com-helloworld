# Serverless.com Tutorials

## About

This is code I wrote while going through the [serverless.com](https://serverless.com) Getting Started tutorials.

## How to run

Install servervless with NPM and then you should just be able to run:

  serverless deploy --aws-profile [ENTERPROFILENAMEHERE]

You might also want to edit the serverless.yml files and rename the functions to something else (I've been using
"srdan").

## How to delete

Delete with:

  serverless remove --aws-profile [ENTERPROFILENAMEHERE]

## Other notes

For the Python/Flask example you need to make sure you have the virtual environment set up and that if you're using
Python3 you upgrade to 3.6 as otherwise "pip" complains about the TLS versions coming from pypi.org.
