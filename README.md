centos65-lamp
=============

## require
* Git
* Vagrant(https://www.vagrantup.com/)
* VirtualBox(https://www.virtualbox.org/)

## install
`` git clone git@github.com:masusugu/centos65-lamp.git ``  
`` cd centos65-lamp ``  
`` vagrant up ``  

## ssh
`` vagrant ssh ``

## document root
Vagrant側の `` /var/www/html `` がMac側の `` src `` フォルダに対応します。

## environment
* CentOS 6.5
* Apache 2.2
* PHP 5.5
* MySQL 5.6
  * vagrant:vagrant
* Git 1.9
* Vim
