# DOCKER container Switcher

This Bash script for users who work with multple docker containers, make them easy to switch between different docker containers with ease.



## Usage
```bash
$ wget https://raw.githubusercontent.com/alirza143/switch-docker/main/sdocker
$ chmod +x ./sdocker
$ sudo mv sdocker /usr/local/bin/sdocker
$ sudo sdocker
```
Sample output
```text
### when no docker container is running

0 : container1 
1 : container2
2 : container3
3 : container4
Select Docker Container: 2

### if you have already running any container then

0 : container1 
1 : container2
2 : container3 (active)
3 : container4

1 : Restart Container 
2 : Stop This Container 
3 : Start another container
Select above number or press any key to abort : 1
```

> **DISCALIMER:** These instructions are made available for ease and not recommended for the production, owner will not be responsible of any damage or lose of data or whatsoever.
