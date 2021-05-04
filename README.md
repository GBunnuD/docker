# Docker
### What is Docker?
* Docker is used to prevent The Matrix from HELL.
* It is used to run differnt applications in different containers on the same virtual machine.
* We define the properties and components  of the application and other users can directly run the application with the run commnand.
* Each applicatio run with their ownn dependencies in seperatre containers.
* A Docker is not a container nor a VM. It is a combination of both VM amd container.
* A Docker is present in n number of virtual machines, where each VM consists of n number of containers.

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

## Commands
* Command used to run a particular app.

```bash
docker run app
```
* 
 



  
