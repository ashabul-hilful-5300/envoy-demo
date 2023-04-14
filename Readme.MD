docker build -t my-envoy-demo . __
docker run --name my-envoy-demo -d -p 10000:10000 -p 9901:9901 my-envoy-demo 
