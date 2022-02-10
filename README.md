# python_blank

docker container with blank "Hello World" script


# Requirements
* python3.6 or newer
* 

# Setup
* here we assume we install in ```/opt```


## Run with Docker
```
git clone <this_repo_url>
cd python_blank
```


Now you should be able to build and run the image with following commands
```
docker build -t python_blank .
docker run -d 
```

You can alternatively use the provided [docker-compose.yml](docker-compose.yml):
```
docker-compose up -d
```

# License
>You can check out the full license [here](LICENSE.txt)

This project is licensed under the terms of the **MIT** license.
