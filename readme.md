docker build -t slackbot .
docker run --rm -p 49160:8080 --name slackbot slackbot