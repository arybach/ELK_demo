git clone https://github.com/arybach/ELK_demo.git
sudo chown -R 1000:1000 ./elasticsearch/data 

# parsed field with datetime time should be different from the original column name - 
# otherwise it will get converted back to string from the parsed datetime format

# to run 
docker-compose up

# kibana: 127.0.0.1:5601
