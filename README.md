# LDGAK_2020
Levelup Devops using github action and kubernetes

### Create New Project 
````
dotnet new mvc --name ldgak2020 --output .
````

### Build Docker Image 
```
docker build -t ldgak-image -f Dockerfile .
````


### Run Docker Image
`````
$ docker run -d -p 8080:80 --name ldgak-app ldgak-image

````
