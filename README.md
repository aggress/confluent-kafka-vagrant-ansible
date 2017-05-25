# confluent-kafka-vagrant-puppet

# Prerequisites

## On OSX:
brew cask install virtualbox
brew cask install vagrant
brew install ansible
vagrant plugin install vagrant-hostsupdater
vagrant plugin install vagrant-vbguest

## Updated base box
vagrant init centos/7
vagrant ssh
yum update
ctrl +d
vagrant package --output centos7_updated
vagrant box add centos7_updated.box 
