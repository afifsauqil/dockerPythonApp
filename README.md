# dockerPythonApp
docker simple build image using python with CI/CD

build image : 
```
docker build -t python-app .
```

run image :
```
docker run -dp 5000:5000 --name app python-app
```

run image using docker-compose :
```
docker-compose -f docker-compose.dev.yml up --build -d
```

test web app :
```
curl http://localhost:5000
```
