## vagrant
  # https://www.vagrantup.com/
this project present a basic use case of vagrant and will focus on install, setup and run vagrant (on a linux machine)
### Install:
  1- Start by download vagrant from https://www.vagrantup.com/downloads.html and install on your local machine
  
  2- check if everything is well install by running command
  ```
  bash-4.1$ vagrant
  ``` 
### Setup your project
  
  1- create a folder to handle your project 
  ```
  bash-4.1$ mkdir my_simple_vagrant_project
  bash-4.1$ cd my_simple_vagrant_project
  ```
  2- To initialize your project, you should use a Box (more about Box: https://app.vagrantup.com/boxes/search)
     all information about precise64 Box available here : https://app.vagrantup.com/hashicorp/boxes/precise64
  ```
  bash-4.1$ vagrant init hashicorp/precise64
  ``` 
  Now, your project is initilized and you can start intresting things 
