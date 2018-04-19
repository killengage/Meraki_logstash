This is a config-file for use with logstash. Logstash is a module normaly used in combination with Elasticsearch and Kibana. For more information check https://www.elastic.co/. This logstash config will pull data via the Meraki API and send the data to Elasticsearch.


Within the file is a API that pulls MX load as a json perfscore count. Output parameter is "perfScore": [XX]  (json).
For more API's check https://documenter.getpostman.com/view/897512/2To9xm.

Replace were ***-HERE with your own id's , API key. Default index to elasticsearch is log*.

I will update this file later (add custom indexes, filters and so on). When i have time i will also add more configs.

Other usefull API Python scripts: https://github.com/meraki/automation-scripts
