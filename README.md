# An Introduction to Linux as a Development Environment

## Syllabus
- [An Introduction to Linux as a Development Environment](#an-introduction-to-linux-as-a-development-environment)
  - [Syllabus](#syllabus)
    - [Preliminaries](#preliminaries)
    - [Getting a Linux Environment](#getting-a-linux-environment)
    - [Logging into linux](#logging-into-linux)
    - [Using the command line](#using-the-command-line)
    - [An introduction to Docker (or Podman)](#an-introduction-to-docker-or-podman)
    - [An introduction to Ansible](#an-introduction-to-ansible)

### Preliminaries
1. What is Linux and kernels in general
   
   [Linux](https://en.wikipedia.org/wiki/Linux)

   [Kernels](https://en.wikipedia.org/wiki/Kernel_(operating_system))
2. Base programs and the GNU Project
3. Free Software and Open Source Software
4. Linux Distributions
   1. Debian Based
   2. Red Hat Based
5. A quick note about hardware architectures
   1. X86 X64
   2. ARM
### Getting a Linux Environment
1. Windows and WSL
2. Windows and Dual Boot
3. MacOs and BSD
4. Linux on bare metal
5. Virtual Machines
6. Linux on the cloud

### Logging into linux
1. The Linux Console
2. Command line sessions with SSH
   1. Interactive session
   2. Remote command execution
   3. Port forwarding
   4. Tunneling
   5. Jump Hosts
   6. ssh dministrativia:
      1. authorized_keys
      2. known_hosts
      3. ssh_keygen: key generation, key comments, deletion of know hosts
3. File transfers with SSH
   1. sftp
   2. scp
4. Graphical User Interface
   1. Gnome
   2. KDE
   3. Xfce
   4. vnc and xrdp
   5. Apache Guacamole

### Using the command line
1. Working with files
   1. Listing files
   2. Permissions and ACLs
   3. Special permissions: Set UID, Set GID
   4. Creating directories (folders)
   5. Current and parent directories
   6. Full and relative paths
2. Getting help
   1. The `man` command
   2. The `apropos` command
3. Finding things
   1. The `whereis` command
   2. The `find` command
4. Connecting commands
   1. stdin, stdout, stderr
   2. Redirecting stdout
   3. Redirecting stderr
   4. Redirecting stdin
   5. Connecting stdout to stdin
5. Editing files
   1. `nano`
   2. `vi`
6. Other useful commands
   1. `cut`
   2. `awk`
   3. `grep`
   4. `xargs`
7. An Introduction to `bash` Shell Scripting
   1. hash bang
   2. `echo`
   3. variables
   4. `if`
   5. `for`
   6. `while`
8. An Introduction to `awscli`
   1. credentials and profiles
   2. `s3`
   3. `ec2`
9. Network
   1.  `netstat`
   2.  `ss`
   3.  `ping`
   4.  `traceroute`
   5.  `nslookup`
   6.  `dig`
10. Web developemnt
    1.  `git`
    2.  `curl`
    3.  Publishing a site with Apache Web Server
    4.  What it takes to make a website use SSL
        1.  DNS
        2.  Lets Encrypt
11. Finding what is wrong
    1.  `/var/log`
    2.  `tail`
 

### An introduction to Docker (or Podman)

### An introduction to Ansible