# What is Docker?

In a very summarised way, we can say that Docker is an open platform, created with the goal of facilitating the development, deployment and execution of applications in isolated environments. It was designed especially to make an application available in the fastest way as possible.

![](images/docker.jpg)
 



To create the required isolation in the process, Docker uses the kernel functionality, called [namespaces](http://man7.org/linux/man-pages/man7/namespaces.7.html), that creates isolated environments between containers: the processes of a running application will not have access to the resources of another one. Unless it is expressly enabled in the configuration of each environment. 
