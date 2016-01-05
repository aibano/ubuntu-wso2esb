# Introduction
This WSO2ESB image is built based on [aibano/ubuntu-java-8 Image](https://hub.docker.com/r/aibano/ubuntu-java-8/)

## Usage
- To run: `docker run -d -p 9443:9443 -p 9763:9763 -p 8243:8243 -p 8280:8280 aibano/ubuntu`
- To run with data volume: `docker run -d -p 9443:9443 -p 9763:9763 -p 8243:8243 -p 8280:8280 -v /opt/wso2esb-4.9.0/repository aibano/ubuntu`
