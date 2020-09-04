# psycopg2 2.8.5 for Python 3.8 -- A Layer to Use When Deploying to AWS Lambda
Source files to use for creating a psycopg2 lambda layer specifically for Python 3.8. Uses psycopg2 2.8.5

To use this, clone the repo and copy the psycopg2 directory into your AWS Lambda project. Then, when you build the AWS Lambda zip package, the layer will install upon deployment.

If you are looking for psycopg2 support for Python 3.6 or 2.x, it has graciously been hosted in this repo:
https://github.com/jkehler/awslambda-psycopg2

This was just made for Python 3.8/psycopg2 2.8.5 in case any users needed this layer and didn't want to compile it themselves.
