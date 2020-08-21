# Start docker ES cluster
docker-compose up -d --remove-orphan

# Stop docker ES cluster
- docker-compose down

# Status of ES cluster
- docker ps

# Access Elastic search
- http://localhost:9200

# Access Kibana
- http://localhost:5601

# Log stash in listening for file beat log on port 5044, please use filebeat.yml bellow for your filebeat

# to install Logstash standalone outside of DOcker use logstash-standalone.conf, it will scan the log from file directly
