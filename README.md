Elasticsearch security features have been automatically configured!
✅ Authentication is enabled and cluster connections are encrypted.

ℹ️  Password for the elastic user (reset with `bin/elasticsearch-reset-password -u elastic`):
  oczXG=Dpl-jSt-T4TUlG

ℹ️  HTTP CA certificate SHA-256 fingerprint:
  f049cbb08a5777b1b8acf2c246ad2337dbceb30f5c7c6dbacbf440733dd5474e

ℹ️  Configure Kibana to use this cluster:
• Run Kibana and click the configuration link in the terminal when Kibana starts.
• Copy the following enrollment token and paste it into Kibana in your browser (valid for the next 30 minutes):
  eyJ2ZXIiOiI4LjEzLjMiLCJhZHIiOlsiMTAuNC4xNTIuMTUyOjkyMDAiXSwiZmdyIjoiZjA0OWNiYjA4YTU3NzdiMWI4YWNmMmMyNDZhZDIzMzdkYmNlYjMwZjVjN2M2ZGJhY2JmNDQwNzMzZGQ1NDc0ZSIsImtleSI6IndXSUtWNDhCb0dGdUFQT2Z4Y0RNOnlsQkF0VzFZUmVPVkNZdS1PQTEwN2cifQ==

ℹ️  Configure other nodes to join this cluster:
• On this node:
  ⁃ Create an enrollment token with `bin/elasticsearch-create-enrollment-token -s node`.
  ⁃ Uncomment the transport.host setting at the end of config/elasticsearch.yml.
  ⁃ Restart Elasticsearch.
• On other nodes:
  ⁃ Start Elasticsearch with `bin/elasticsearch --enrollment-token <token>`, using the enrollment token that you generated.