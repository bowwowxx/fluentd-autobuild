# fluentd-autobuild

fluentd Collector
fluentd container for development use
docker run -d -it -p 7777:7777 -v /Users/andy/github/fluentd-autobuild:/fluentd/etc/ --name=fluentd bowwow/collector

curl -H "Content-Type: application/json" -X POST -d '{"username":"xyz2","password":"xyz2"}' http://xxx
