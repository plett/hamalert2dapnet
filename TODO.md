I'm going to be doing this over time. This is a task list of things which are
going to be required.

# pre-reqs

* [x] Build a PoC AWS API GW and Python helloworld Lambda to learn

# v0.1

## Recieving from HAMAlert

* [x] Look at what HAMAlert will send us. (POST, we want the "title" parameter)
* [x] Get a HAMAlert account to test with
* [x] Write PoC Lambda to receive and log title parameter

## Sending to DAPNET

* [x] RTFM and find how to inject messages into DAPNET
	https://hampager.de/dokuwiki/doku.php?id=start#dapnet_api
* [ ] Get a DAPNET account
* [ ] curl some test messages into DAPNET

## Write app

* [ ] Write Lambda to receive HAMAlert messages on a unique per-user URL and
  send it to DAPNET based on hard coded auth, destination callsign etc which are
  stored in environment variables
* [ ] Ship it

# v1.0

Note, this may never happen!

##

* [ ] A DynamoDB to store the unique URL, destination callsign and tx group so
  it can be used by multiple users
* [ ] A CRUD app so users can self-service accounts in the DynamoDB

