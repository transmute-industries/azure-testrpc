# Azure TestRPC


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