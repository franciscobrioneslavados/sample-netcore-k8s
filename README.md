docker build -t sample-netcore .

docker run -d -p 8080:80 --name sample-netcore-v6 sample-netcore

http://localhost:8080/

docker images

docker tag [IMAGE_ID] 167235042/sample-netcore:latest

docker push 167235042/sample-netcore