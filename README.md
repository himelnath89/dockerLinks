# dockerLinks
ctrl+c to stop docker command

echo GET | openssl s_client -CApath /etc/ssl/certs/ -connect api.nuget.org:443 2>&1

 create sample to check image works fine

docker run -it --rm mcr.microsoft.com/dotnet/core/sdk:3.1 ping www.google.com

docker run -it --rm mcr.microsoft.com/dotnet/core/sdk:3.1 ping api.nuget.org

https://github.com/dotnet/dotnet-docker/blob/main/samples/run-aspnetcore-https-development.md

https://github.com/dotnet/dotnet-docker/blob/main/samples/host-aspnetcore-https.md

How to create certificate from url: openssl s_client -connect google.com:443 2>/dev/null | openssl x509> google.com.pem


From Dan

dotnet YouApp.dll --urls http://0.0.0.0:8080

netstat -tln

sudo docker exec –it nginx-test /bin/bash

docker ps

docker container ls

