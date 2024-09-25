# Docker
**Docker** is a set of Platforms as a service (PaaS) products that use Operating system-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries, and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating system kernel and therefore use fewer resources than a virtual machine.<BR/>
![image](https://github.com/user-attachments/assets/e18eccba-564e-4955-a8eb-9a92e7be4999)

# Key features of Docker:
**Containerization** :<br/>
Containerization is a virtualization technique that packages an application and its dependencies into a standardized unit called a container. Docker is a popular containerization platform that allows developers to build, ship, and run containers. <br/>
<br/>
**Docker Hub**:<br/>
Docker Hub is a container registry built for developers and open source contributors to find, use, and share their container images. With Hub, developers can host public repos that can be used for free, or private repos for teams and enterprises.<br/>
<br/>
**Docker image**:<br/>
Docker image is a file that contains the instructions for running code in a Docker container<br/>
<br/>
**Dockerfile**:<br/>
Dockerfile is a text file that contains instructions for building a Docker image.<br/>
<br/>
**Orchestration**:<BR/>
Docker orchestration is a set of tools and practices that help manage Docker containers at scale.<BR/>
# Docker Commands
Through introducing the essential docker commands, docker became a powerful software in streamlining the container management process. It helps in ensuring a seamless development and deployment workflows. The following are the some of docker commands that are used commonly:
<br/>
<br/>
**Docker Run**: It used for launching the containers from images, with specifying the runtime options and commands.<br/>
<br/>
**Docker Pull**: It fetches the container images from the container registry like Docker Hub to the local machine.<br/>
<br/>
**Docker ps** : It helps in displaying the running containers along with their important information like container ID, image used and status.<br/>
<br/>
**Docker Stop** : It helps in halting the running containers gracefully shutting down the processes within them.<br/>
<br/>
**Docker Start**: It helps in restarting the stopped containers, resuming their operations from the previous state.<br/>
<br/>
**Docker Login**: It helps to login in to the docker registry enabling the access to private repositories.<br/>
<br/>
# Container in Docker
A Docker container is a package that contains all the components required to run an application, including the code, dependencies, and libraries. Docker containers are lightweight and portable, and can run on any system that has a Linux or Windows operating system.<br/>
<br/>
**Here are some benefits of Docker containers**: <br/>
<br/>
**Lightweight**: Containers share the same operating system kernel as the machine they're running on, so they don't need their own operating system. <br/>

**Secure**: Applications are safer when running in containers. <br/>

**Portable**: Containers can be moved to any system that runs Linux or Windows. <br/>
<br/>
# NGINX
NGINX is open-source web server software used for reverse proxy, load balancing, and caching. It provides HTTPS server capabilities and is mainly designed for maximum performance and stability. It also functions as a proxy server for email communications protocols, such as IMAP, POP3, and SMTP. 
**The NGINX Architecture**
By implementing event-driven, asynchronous, and non-blocking models, NGINX uses master-slave architecture.<br/>
<br/>
It also uses an advanced event-based mechanism in many operating systems. Additionally, NGINX uses multiplexing and event notifications and dedicates specific tasks to separate processes. For example, if you have 10 tasks, 10 different processes will handle each of them. NGINX processes highly efficient run loops in a single-thread process called workers.<br/>
<br/>
**Workers** accept new requests from a shared listen socket and execute highly efficient run loops inside each worker to process thousands of requests. <br/>
<br/>
**Masters** read and validate configurations by creating, binding, and crossing sockets. They also handle starting, terminations, and maintaining the number of configured worker processes. The master node can also reconfigure the worker process with no service interruption.<br/>
<br/>
**Proxy caches** are special processes. They have a cache loader and manager. The cache loader checks the disk cache item and populates the engine’s in-memory database with the cache metadata. It prepares the NGINX instances to work with the files already stored on the disk in a specifically allocated structure. The cache manager handles cache expiration and invalidation.
**Features of NGNIX**<BR/>
**Web Server**: It can serve static content (like HTML, CSS, and images) quickly and efficiently.<BR/>
<BR/>
**Reverse Proxy**: NGINX can act as an intermediary for requests from clients seeking resources from other servers, distributing the load and improving performance.<BR/>
<BR/.
**Load Balancing**: It can distribute incoming traffic across multiple servers to ensure availability and reliability.<BR/>
<BR/>
**SSL/TLS Termination**: NGINX can handle SSL/TLS encryption, improving security while offloading the processing from backend servers.<BR/>
<BR/>
**Caching**: It can cache content to reduce latency and improve response times.<BR/>
<BR/>
**Support for WebSockets**: NGINX supports real-time communication for applications that require persistent connections.<BR/>
