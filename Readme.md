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