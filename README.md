This is a test document for using command script to index into Elasticsearch:

curl -u elastic:123456 -s -H "Content-Type: application/x-ndjson" -XPOST localhost:9200/_bulk --data-binary @es.json

where "123456" is the password for the Elasticsearch and "elastic" is the username
