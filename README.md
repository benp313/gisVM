# gisVM
A vagrant/ansible based virtual machine definition for using QGIS.

## Installation

Install vagrant and ansible using [homebrew](http://brew.sh).

Clone this repo using a recursive checkout command, such as:

> `git clone --recursive https://github.com/benp313/gisVM.git`


Open a terminal, and navigate to the directory into which you cloned this repo. Then execute:

> `./vagrantism/ansiblePlaybooks/linkVagrantism.sh ansible/`

To launch the VM, change to the VM directory and execute `vagrant up`.