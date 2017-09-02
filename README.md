# Azure TestRPC

https://testrpc.azurewebsites.net/

[Setup Docker on Azure](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-linux-using-custom-docker-image)

### Docker
```
$ docker build -t or13/testrpc ./testrpc
$ docker run --rm -p 8545:8545 -it or13/testrpc 
$ docker push or13/testrpc
```

### Node
```
$ npm run testrpc
$ npm run test
```