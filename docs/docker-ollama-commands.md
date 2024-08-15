docker run hello-world
    2  df -h
    3  cd /dev/nvme0n1p2
    4  mkdir workspace
    5  cd workspace/
    6  mkdir 
    7  mkdir open-source
    8  cd open-source/
    9  mkdir ollamaFolder
   10  cd ollamaFolder/
   11  pwd
   12  docker run -d --gpus=all -v /home/hoop/workspace/open-source/ollamaFolder/ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
   13  distribution=$(. /etc/os-release;echo $ID$VERSION_ID)       && curl -s -L https://nvidia.github.io/libnvidia-container/gpgkey | sudo apt-key add -       && curl -s -L https://nvidia.github.io/libnvidia-container/$distribution/libnvidia-container.list | sudo tee /etc/apt/sources.list.d/nvidia-container-toolkit.list
   14  sudo apt-get update
   15  sudo rm '/etc/apt/sources.list.d/playonlinux.list'
   16  sudo apt-get update
   17  rm /etc/apt/sources.list.d/nvidia-container-toolkit.list
   18  sudo apt-get update
   19  sudo apt-get install -y nvidia-docker2
   20  curl -s -L https://nvidia.github.io/nvidia-docker/$distribution/nvidia-docker.list |   sudo tee /etc/apt/sources.list.d/nvidia-docker.list
   21  sudo apt-get install -y nvidia-docker2
   22  pwd
   23  cd workspace/open-source/ollamaFolder/
   24  ls
   25  ls ollama/
   26  cd ollama/
   27  #docker run -d --gpus=all -v /home/hoop/workspace/open-source/ollamaFolder/ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
   28  docker run -d --gpus=all -v /home/hoop/workspace/open-source/ollamaFolder/ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
   29  docker ps
   30  docker ps -a
   31  8e7308b57ba0
   32  docker run 8e7308b57ba0
   33  docker ps -a
   34  docker start 8e7308b57ba0
   35  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   36  sudo apt-get install nvidia-container-toolkit
   37  cat  /etc/apt/sources.list.d/nvidia-docker.list
   38  sudo apt-get update
   39  sudo apt-cache search nvidia | grep container
   40  sudo apt-get install -y nvidia-container-toolkit
   41  sudo apt-get update && sudo apt-get install -y nvidia-container-toolkit
   42  wget https://nvidia.github.io/nvidia-docker/gpgkey --no-check-certificate
   43  sudo apt-key add gpgkey
   44  distribution=$(. /etc/os-release;echo $ID$VERSION_ID)
   45  docker ps -a
   46  docker start 8e7308b57ba0
   47  sudo apt install -y nvidia-docker2
   48  sudo apt-get remove docker docker-engine docker.io
   49  docker ps
   50  sudo apt-get install     apt-transport-https     ca-certificates     curl     software-properties-common
   51  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   52  sudo apt-key fingerprint 0EBFCD88
   53  sudo add-apt-repository    "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
   54  sudo apt-get update
   55  sudo apt-get install docker-ce
   56  sudo apt-get install nvidia-docker2
   57  cat nvidia-docker.lis
   58  cat nvidia-docker.list
   59  curl -s -L https://nvidia.github.io/nvidia-docker/ubuntu20.04/nvidia-docker.list > /etc/apt/sources.list.d/nvidia-docker.list
   60  cat nvidia-docker.list
   61  cat /etc/apt/sources.list.d/nvidia-docker.list
   62  sudo apt-get update
   63  sudo apt-get install nvidia-docker2
   64  docker start 8e7308b57ba0
   65  sudo apt-get update
   66  docker start 8e7308b57ba0
   67  curl -s -L https://nvidia.github.io/nvidia-docker/$distribution/nvidia-docker.list 994 | sudo tee /etc/apt/sources.list.d/nvidia-docker.list
   68  sudo systemctl daemon-reload
   69  sudo systemctl restart docker
   70  docker ps -a
   71  docker start 8e7308b57ba0
   72  docker ps
   73  docker exec -it ollama ollama run lamma2
   74  docker exec -it ollama ollama run llama2
   75  docker ps

