# TwitterDB
Twitter Live streaming.

# How to RUN this
- `mkdir twitterLive`
- `git init`
- `git pull https://github.com/jinesh90/TwitterDB.git`
- `echo "ELK_VERSION=6.8.12" >> .env`
- `docker-compose build`
- `docker-compose up`
-`After some time you will see ELK stack is up and running, goto http://localhost:5601 and enter user:elastic password:changeme`
-`Create index with "*" and see live tweet data coming from your area`
