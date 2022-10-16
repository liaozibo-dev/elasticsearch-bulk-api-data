This is a test document for using command script to index into Elasticsearch:

Git Bash：
```
curl --cacert config/certs/http_ca.crt -u elastic:password -s -H "Content-Type:application/x-ndjson" -XPOST https://localhost:9200/_bulk --data-binary @example/es.json
```

where "password" is the password for the Elasticsearch and "elastic" is the username