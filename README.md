# fabric-sdk-go-application
this is a fabric-sdk-go application of web, just help me be familiar with fabric web


## environment
ubuntu 16.04

docker 19.03.5

go 1.12.12

etc...


## Start
cd fixtures

docker-compose down

rm -rf /tmp/kongyixueyuan-*

docker rm -f -v docker ps -a --no-trunc | grep "kongyixueyuan" | cut -d ' ' -f 1 2>/dev/null

docker rmi docker images --no-trunc | grep "kongyixueyuan" | cut -d ' ' -f 1 2>/dev/null

cd …

make


## Test
http://localhost:9000
