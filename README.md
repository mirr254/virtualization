## Virtualisation made easy

This repo describes how to create a virtual machine. To be more precise, a windows server 2016 virtual machine.

To get a brief overview of why we need to do this, head over to [ This article](https://www.m.com)

Fisrt up, clone the repo and cd into directory  
`git clone https://github.com/mirr254/virtualization.git` 

`cd virtualization`

Before moving on, make sure vagrant is installed or install it by running 
`brew cask install vagrant`

Also make sure virtualbox is installed. You can install it by running

`brew cak install virtualbox`

### Setting up

Since we have the `Vagrantfile` we don't need to run `vagrant init` which creates a vagrant file with all the required configuration.

run `vagrant up` and wait for the download to finish.

Once done, you can `ssh` into the box by running  
`vagrant ssh`

Once you have a shell you can poke around. 

Good luck!!

