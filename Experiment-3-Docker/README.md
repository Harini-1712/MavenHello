\# Experiment 3: Docker Container Execution



\## Aim

To install Docker Desktop and execute an Ubuntu container on Windows 11.



\## Requirements

\- Windows 11

\- Docker Desktop

\- WSL 2

\- Internet connection



\## Commands Executed



\### 1. Check Docker version

```bash

docker --version

```



\### 2. Test Docker installation

```bash

docker run hello-world

```



\### 3. Download and run Ubuntu container

```bash

docker run -it ubuntu bash

```



\### 4. Check Ubuntu version

```bash

cat /etc/os-release

```



\### 5. Verify container information

```bash

docker images

docker ps

docker ps -a

```



\## Result

Docker was successfully configured on Windows 11. The Hello World container executed successfully, and the Ubuntu container was created and tested.

