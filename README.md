# Why should we use SSH with Git-hub

## SSH keys and Git-hub
### There are two methods to clone the repo

``` SSH AND HTTPS ```
- We have two types repos ```public repo``` 
- second is ```private repo```
- generate SSH keys on your local system
- copy the key from local system to the specific repo on git-hub (ci-start-code)
- name new key as your name (AgboLamina)
- cat filename.pub
- copy the key
- go to your git-hub to the specific repo
- click on settings
- click on deploy keys
- add name and paste link to key

### Step by step breakdown
- cd
- ls -a
- cd .ssh
- ls
- ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
- AgboLamina
- (enter) x2 (no passcode)

### It is essential and the best practice to write descriptive name eg. Agbo-jenkins
