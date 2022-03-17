# AppArmor in Ubuntu



AppArmor support was first introduced in Ubuntu 7.04, and is turned on by  default in Ubuntu 7.10 and later. AppArmor confinement in Ubuntu is  application specific with profiles available for specific binaries. With each release, [more and more profiles](https://wiki.ubuntu.com/SecurityTeam/KnowledgeBase/AppArmorProfiles) are shipped by default, with [more planned](https://wiki.ubuntu.com/SecurityTeam/Roadmap#AppArmor_Confinement). 

If a profile is not available for an application, users may create a  profile and add it to /etc/apparmor.d. If a profile is not defined for a particular binary, the binary is not confined. See [More information](https://wiki.ubuntu.com/AppArmor#More_information) for details. 

配置文件存储在/etc/apparmor.d目录中。 这些配置文件是纯文本文件，可以包含注释

































## More information



- [Ubuntu AppArmor Documentation](https://help.ubuntu.com/community/AppArmor) 

- [AppArmor Features](https://wiki.ubuntu.com/Security/Features#apparmor) 

- Ubuntu 12.04 ESM (Precise Pangolin) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/precise/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/precise/en/man5/apparmor.d.5.html) 

- Ubuntu 14.04 ESM (Trusty Tahr) 

  

  - [Server Guide - AppArmor](https://help.ubuntu.com/14.04/serverguide/apparmor.html) 
  - [apparmor man page](https://manpages.ubuntu.com/manpages/trusty/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/trusty/en/man5/apparmor.d.5.html) 

- Ubuntu 16.04 LTS (Xenial Xerus) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/xenial/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/xenial/en/man5/apparmor.d.5.html) 

- Ubuntu 18.04 LTS (Bionic Beaver) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/bionic/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/bionic/en/man5/apparmor.d.5.html) 

- Ubuntu 20.04 (Focal Fossa) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/focal/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/focal/en/man5/apparmor.d.5.html) 

- Ubuntu 21.04 (Hirsute Hippo) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/hirsute/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/hirsute/en/man5/apparmor.d.5.html) 

- Ubuntu 21.10 (Impish Indri) 

  

  - [apparmor man page](https://manpages.ubuntu.com/manpages/impish/en/man7/apparmor.7.html) 
  - [apparmor.d man page](https://manpages.ubuntu.com/manpages/impish/en/man5/apparmor.d.5.html) 

- Technical documentation can be found in `/usr/share/doc/apparmor-docs/techdoc.pdf.gz` from apparmor-docs package 

- [AppArmor upstream documentation](https://gitlab.com/apparmor/apparmor/-/wikis/Documentation) 

- [AppArmor upstream wiki](http://wiki.apparmor.net/) 

- [AppArmor specification](https://wiki.ubuntu.com/SecurityTeam/Specifications/AppArmor) for Ubuntu 

- See the [DebuggingApparmor](https://wiki.ubuntu.com/DebuggingApparmor) page for how to troubleshoot AppArmor in Ubuntu 



AppArmor  (last edited 2021-10-17 00:04:50 by [sbeattie](https://launchpad.net/~sbeattie))