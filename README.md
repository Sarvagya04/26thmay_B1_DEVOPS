

# Task1 ScreenShot
![task1 day17](https://user-images.githubusercontent.com/85029049/123080782-e891e800-d43a-11eb-99a5-ff8b66ac1634.png)


# Task1 TextFile
```
sudo apt-get remove docker docker-engine docker.io containerd runc
sudo apt-get update
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo \
  "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
Give user Sudo Permissions to Access Docker
```
sudo usermod -aG docker $USER
newgrp docker 
```


# Task2 SCreenShot
![task2 day17](https://user-images.githubusercontent.com/85029049/123080969-170fc300-d43b-11eb-981a-453c1705458a.png)


# Task2 TextFile
```
docker pull ubuntu:20.04
```
# Task3.1 ScreenShot
![task3 2 day17](https://user-images.githubusercontent.com/85029049/123082033-3ce99780-d43c-11eb-8a2e-add13a877493.png)

# Task3.1 TextFile
Start Process
```
docker run -it ubuntu:20.04 sleep 400
```
# Task3.2 ScreenShot
![task3 1 day17](https://user-images.githubusercontent.com/85029049/123082087-48d55980-d43c-11eb-8169-362f24ed5c03.png)


# Task3.2 TextFile
Pause Process
```
docker pause docker_name
```
# Task3.3 ScreenShot
![task 3 3 day17](https://user-images.githubusercontent.com/85029049/123081574-b8971480-d43b-11eb-9297-8e02ca1490a5.png)

# Task3.3 TextFile
Stop Process
```
docker stop docker_name
```
# Task4 ScreenShot
![task4 day17](https://user-images.githubusercontent.com/85029049/123081718-e1b7a500-d43b-11eb-9280-44ad9f77e3e3.png)

# Task4 TextFile
```
docker run -it ubuntu:20.04 bash
```
