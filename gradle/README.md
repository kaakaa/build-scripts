```
docker build -t gradle-bootstrap .
docker run -v $PWD/app:/usr/local/src gradle-bootstrap test
```
