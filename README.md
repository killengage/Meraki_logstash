This is a config-file for use with logstash. Logstash is a module normaly used in combination with Elasticsearch and Kibana. For more information check https://www.elastic.co/. This logstash config will pull data via the Meraki API and send the data to Elasticsearch.


Within the file is a API that pulls MX load as a json perfscore count. For more API scripts check https://github.com/meraki/automation-scripts.

Replace were ***-HERE with your own id's , API key. Default pattern to elasticsearch is log*.
