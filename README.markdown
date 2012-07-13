## GMail OAuth2 Sinatra

* It should be known that GMail is currently not supported with OAuth2 as far as I can tell.

A small working example of interacting with the Google API using OAuth and Sinatra

## Pre Reqs

Head to https://code.google.com/apis/console/, from the left menu select API Access and create a Client ID

## Run It!

To get this puppy running you just need to:

```bundle install```

then

```G_API_CLIENT=<your_client_id> G_API_SECRET=<your_secret> rackup```

and then head over to http://localhost:9292 and click the 'Auth' link
