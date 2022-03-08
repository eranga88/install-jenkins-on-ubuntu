# install-jenkins-on-ubuntu

    1  sudo apt update
    2  sudo apt install openjdk-11-jdk-headless
    3  sudo apt update
    4  sudo apt upgrade
    5  sudo apt install wget
    6  wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
    7  sudo sh -c 'echo deb http://pkg.jenkins.io/debian binary/ > /etc/apt/sources.list.d/jenkins.list'
    8  sudo apt update
    9  sudo apt upgrade
   10  sudo apt install jenkins
   11  sudo systemctl start jenkins
   12  sudo systemctl status jenkins
   13  sudo systemctl enable jenkins
   14  sudo systemctl status jenkins
   15  clear
   16  history
