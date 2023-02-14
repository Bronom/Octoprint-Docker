# Octoprint-Docker
 Cheap Installation script for Octoprint

**********************
IMPORTANT

Allways execute every command command in Requirement.txt before any .sh script.

**********************
Every script and command are tested through SSH with SolarPutty.

Script tested : 

 - Requirement.txt

 - install_docker.sh

**********************
Explication :

You can copy paste the command from any installation script (.sh) inside the install_docker.sh to be easier to run.

Feel free to edit the script.

**********************
What the script is doing ?

The Requirement.txt command : 

- Enable the "permanant" sudo mode

- Go to the root folder

- Remove possible older version of the git repo

- Create folder "dockercomposegit"

- Select the folder

- Clone the repo in the folder

- Select Octoprint-Docker folder

- Give permission to execute script.

For the others script, check comments inside the file.

**********************
Instruction :

Warning : The requirement.txt command do "sudo -s". But, you may need to do "sudo -s" manualy before executing the command / script.

1. Copy & Paste command in Requirement.txt into your terminal to setup the folder and clone the repo. (Inside the requirement.txt, you can remove the # before the command you want to execute the script automaticly)

2. Execute the installation script you want. Exemple : ./install_docker.sh

3. The most important... Wait and watch the magic happening ! 

**********************
Usefull commande to find the good usb port : 

- dmesg | grep tty

- ls /sys/class/tty/ttyUSB* 

- ls /sys/class/tty

*********************
Command to edit docker-compose file

nano /dockercomposegit/Compose/octoprint/docker-compose.yml

CTRL + C To quit and save
