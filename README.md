# systools

Collection of Sysadmins daily handy tools

# Linux

## Kernel

* [Writing a Simple Linux Kernel Module](https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234)

## Red Hat/Fedora

* Yum to DNF [Cheatsheet](https://fedoraproject.org/wiki/Yum_to_DNF_Cheatsheet)

### RPM

#### Build

* [Creating RPM Packages with Fedora](https://fedoraproject.org/wiki/How_to_create_an_RPM_package)
* Spec file, to create lsutil rpm: [here](https://github.com/pld-linux/lsiutil)

## Storage

* [Mounting a hard disk image including partitions using Linux](http://www.andremiller.net/content/mounting-hard-disk-image-including-partitions-using-linux)

### Controllers

* LSILogic util: [lsiutil](https://github.com/kojack/lsiutil)

# Automation

## Ansible

Some usefull ansible scripts and tips on [ansible](./ansible) dir.
* [Playbooks and roles for installing and managing Ansible networking CI](https://github.com/ansible/network-infra-playbooks)
* [Ansible Role: EPEL Repository](https://github.com/geerlingguy/ansible-role-repo-epel)
* [Ansible role to install and manage nginx configuration](https://github.com/jdauphant/ansible-role-nginx)

## Puppet

* [running puppet on openwrt](https://github.com/solarkennedy/puppet-on-openwrt) (dead!)

# Security

## Auditing

* [A UNIX security auditing tool based on several security frameworks](https://github.com/lateralblast/lunar)

## Hardening

* [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html) by [stribika](https://github.com/stribika)
* See your site config with [Hardenize](https://www.hardenize.com/)
* Nice article with a lot of resources: [Common approaches to securing Linux servers and what runs on them.](https://medium.com/@ageis/common-approaches-to-securing-linux-servers-and-what-runs-on-them-dadcacc5388b)
* A lot of good posts by geek flare: 
  * [How to Configure SSL Certificate on Google Cloud Load Balancer?](https://geekflare.com/google-load-balancer-enable-ssl/)
  * [Nginx Web Server Security & Hardening Guide](https://geekflare.com/nginx-webserver-security-hardening-guide/)
  * [IBM HTTP Server Security & Hardening Guide](https://geekflare.com/ibm-http-server-security-guide/)
  * [Apache Tomcat Hardening and Security Guide](https://geekflare.com/apache-tomcat-hardening-and-security-guide/)
  * [How to Enable TLS 1.3 in Nginx, Cloudflare?](https://geekflare.com/enable-tls-1-3/)
  * [Apache Web Server Hardening & Security Guide](https://geekflare.com/apache-web-server-hardening-security/) (broken!??)
* [How do I prevent apache from serving the .git directory?](https://serverfault.com/questions/128069/how-do-i-prevent-apache-from-serving-the-git-directory/128082#128082)

# Containers

* [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)
* [Imagem CentOS7 com firefox ESR e warsaw configurado.](https://github.com/jsalatiel/wsbb-docker) (pt-BR) and [other](https://gist.github.com/dmouse/e76ce3d8dde00fe496da)
* [google chrome](https://github.com/c0b/chrome-in-docker) dockerized and [headless google chrome](https://github.com/eirslett/chrome-karma-docker), [another](https://github.com/miyakogi/pyppeteer)
* Some [fedora](https://github.com/fedora-cloud/docker-brew-fedora/) and [docker](https://docs.docker.com/samples/) links:
  * [Webapps with Docker](https://github.com/docker/labs/blob/master/beginner/chapters/webapps.md)
  * Various great [Dockerfiles](https://github.com/jessfraz/dockerfiles) by jessfraz (as usual)
* [Running a GUI application in a Docker container](https://linuxmeerkat.wordpress.com/2014/10/17/running-a-gui-application-in-a-docker-container/)


# CI

* [Danger](https://github.com/danger/danger) runs after your CI, automating your team's conventions surrounding code review.
* [The centralized Danger server, freeing Danger from running on CI.](https://github.com/danger/peril)

# Interfaces

* [A sysadmin login session in a web browser](https://github.com/cockpit-project/cockpit)

# Troubleshooting

* [sysdig](https://github.com/draios/sysdig): Linux system exploration and troubleshooting tool with first class support for containers

# Shell

* [Software development using Bash](https://oscarforner.com/2018/02/24/Software_development_using_Bash)
* Bashrc files:
   * [Paul's .bashrc](https://github.com/paulkaefer/.bashrc)
   * [rkirti/bashrc](https://github.com/rkirti/bashrc)
* DotFiles: 
   * Amazing collection by [jessfraz](https://github.com/jessfraz/dotfiles/)
   * Some [dotfile](https://github.com/maitesin/dot-files) by maitesin
* Powerline:
   * [Powerline Gitstatus](https://github.com/jaspernbrouwer/powerline-gitstatus)
   
# Other Resources

  * [16 Linux Books and Videos for System Administrator](https://geekflare.com/linux-books-videos/)
  
# VMware

* [The ghettoVCB](https://github.com/lamw/ghettoVCB) script performs backups of virtual machines residing. Here on [VMware Communities](https://code.vmware.com/samples/822/ghetto-vcb?h=Sample)

# Support

## Video Conference

* [Hublin](https://github.com/linagora/hublin): An easy and free video conference service based on WebRTC

# Management

* [8 Patterns for Decentralised Organising](https://standupdev.com/wiki/doku.php?id=patterns_for_decentralised_organising)

---

# Organization

* [Shiori](https://github.com/RadhiFadlillah/shiori) is a simple bookmarks manager written in Go language
