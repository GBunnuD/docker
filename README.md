# Docker
### What is Docker?
* Docker is used to prevent [The Matrix from HELL](https://www.google.com/search?q=what+is+the+matrix+from+hell&rlz=1C5CHFA_enUS941US941&sxsrf=ALeKk02xjUot6N9598DNY-Kp8yUYhXMKPw%3A1620244213232&ei=9faSYJSpDcHktQXS1KLoAQ&oq=what+is+the+matrix+from+hell&gs_lcp=Cgdnd3Mtd2l6EAMyBQgAEM0COgcIIxCwAhAnUMhTWIBcYP5daABwAngAgAGRAYgBjgeSAQM0LjWYAQCgAQGqAQdnd3Mtd2l6wAEB&sclient=gws-wiz&ved=0ahUKEwjU95yGqLPwAhVBcq0KHVKqCB0Q4dUDCBE&uact=5).
* It is used to run differnt applications in different containers on the same virtual machine.
* We define the properties and components  of the application and other users can directly run the application with the run commnand.
* Each applicatio run with their ownn dependencies in seperatre containers.
* A Docker is not a container nor a VM. It is a combination of both VM amd container.
* A Docker is present in n number of virtual machines, where each VM consists of n number of containers.
* WHY?
* Before the Developers used to develop an application and send all the system requirements and libraries to the Operation Team. If there were any isssues in hosting the Operation team will have no knowlege on the code and itr was difficult to communicate with the developer team and get things fixed.
* Using Docker, the developer team will generate an image which will have all the requirements in it, the Operation team will simply use the image to get the apllication as the developers have built the application with all requirements.

### Waht are Containers?
* Containers are completely seperate isolate environment which can have their own services, processors  and mounts but share a common OS Kernal.

### VM v/s Containers
* <table>
<thead>
  <tr>
    <th> VM</th>
    <th>Container</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>VM's utilise more of the system ram, processor and memory.</td>
    <td>Containers are light weight and require less memory and utilization of the system is less.</td>
  </tr>
  <tr>
    <td>It takes more time to start a VM as it has to boot the entire OS. </td>
    <td>It takes less time as a container is light weight and usually it is in MB.</td>
  </tr>
  <tr>
    <td>VM's have complete isolation.</td>
    <td>Containers have isolated envirnments but more resources are shared as they all run usin gthe same Kernal.</td>
  </tr>
  <tr>
    <td>VM's does not underly on the OS. So they can run and OS based application.</td>
    <td>A container cannot run any OS baswed application. It can only run certain application depending on the Kernal.</td>
  </tr>

</tbody>
</table>
### Containers v/s Image
<table>
<thead>
  <tr>
    <th>Container</th>
    <th>Image</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Containers are running instances of Images which are isolated and have their own environments instead or processors.</td>
    <td>An Image a package or template. It is used to create one or more containers</td>
  </tr>
  
</tbody>
</table>

## Commands
* Command used to run a particular app.

```bash
docker run app
```
* For checking the number of images on your system we use the following command –
```bash
$ docker images
```
* For searching an image in the Docker Hub-
```bash
$ docker search <image>
```
*  Runs a command in a new container.
```bash
docker run 
```

* Starts one or more stopped containers
```bash
docker start 
```

* Stops one or more running containers
```bash
docker stop
```

* Builds an image form a Docker file
 ```bash
docker build
```
* Pulls an image or a repository from a registry
```bash
docker pull
```
* Pushes an image or a repository to a registry
```bash
docker push 
```

* Exports a container’s filesystem as a tar archive
```bash
docker export
```

- Runs a command in a run-time container
```bash
docker exec 
```

– Searches the Docker Hub for images
```bash
docker search 
```
– Attaches to a running container
```bash
docker attach 
```

– Creates a new image from a container’s changes
```bash
docker commit 
```
 



  
