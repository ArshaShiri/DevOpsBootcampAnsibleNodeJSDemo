# DevOps Bootcamp Ansible NodeJS Demo

![image](https://github.com/ArshaShiri/DevOpsBootcampAnsibleNodeJSDemo/assets/18715119/b3d0a376-9b2b-4ebd-9a96-ab13d0c25542)

We craetea a very basic droplet on digitalocean.
![image](https://github.com/ArshaShiri/DevOpsBootcampAnsibleNodeJSDemo/assets/18715119/1283a2e5-35be-4afa-b6b0-52a53ea8f2bd)


As a 1st step, the ansible configuration is modified to copy the nodejs package to the server and unpack it.

The unpacked package can be seen on the server:

    root@ubuntu-s-1vcpu-1gb-fra1-01:~# ls
      # app-1.0.0.tgz  package  snap