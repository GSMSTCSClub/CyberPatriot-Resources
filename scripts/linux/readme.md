# Linux CyberPatriot Script

Here is a collection of scripts that can be used to help with CyberPatriot. All
the scripts are written in bash (and or Python) and tested with the latest
version of Ubuntu. The scripts are designed to be run as root.

## Scripts

1. [BiermanM's CyberPatriot Scripts (2016)](https://github.com/BiermanM/CyberPatriot-Scripts)
   - All the user that are kept after the scripts is executed, has a password of
     `Moodle!22`. Further, `root` and all the user accounts that are provided are locked
     from usage with `usermod -L <username>`.
   - The scripts is designed for Ubuntu 16.04 LTS.
   - The scripts disrupt `ssh` connections, so you will have to reconnect to the
     machine after the scripts is executed.
   - Expect a long execution time (>10 minute). This is mainly because the
     inefficient implementation of removing media files in the script (No regex,
     literally listed all the extensions).
   - If the script ask for `yes` or `no`, you must type `yes` or `no`, exactly,
     and there is no default value. Because the horrible comparsion statement,
     you CAN BREAK the script if input contains space, or if you type `y` or
     `n`.
   - If you plan to setup `ssh` service, it will prompt you to type users that
     need `ssh` service one by one.
   - You must unlock the user accounts with `usermod -U <username>` and `root`
     account immediately after execution, if you want to use the machine after
     you run that script.
2. [Dev-Sec's Ansible Collection Hardening](https://github.com/dev-sec/ansible-collection-hardening)
   - This is a collection of Ansible roles that can be used to harden a Linux
     system. The roles are designed to be used with the
     [Ansible Collection Hardening](https://galaxy.ansible.com/devsec/hardening).
   - The collection seems to be broken. However, `os-harden` is the only role
     that is needed for CyberPatriot.
  
------

Not tested.

3. [JShielder](https://github.com/Jsitech/JShielder)
   - Only works with Ubuntu 16.04, 18.04, and Centos 7.
   - A lot of stars and forks. CIS benchmark is compliant.

