# ansible-tomcat

This ansible role installs [Apache Tomcat ](https://tomcat.apache.org/).

>_Warning_
(If needed) the java version installed in Ubuntu 14.04 is 1.7.   Centos 6 , Centos 7 and Ubuntu 16.04 will install java 1.8 .
Also tomcat version is not fixed, this role will always install the latest version of the tomcat package available at the repositories.

Example:
--------

This an example of how to install this role:

    - hosts: server
      roles:
      - { role: ansible-tomcat }
