# A small shim to re-post HamAlert messages to DAPNet

## This is still in the planning stage - no actual code exists here yet.

[HamAlert](https://hamalert.org) is a service which collects Amateur Radio spots
from a variety of sources and send notifications to you when certain criteria
are met.

It can send to a variety of destinations, but [DAPNET](https://hampager.de)
Amateur Radio pagers is not one of them.

This is a very small script to receive HamAlert notifications into an AWS Lambda
and push them out to DAPNET.
