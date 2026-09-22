#                                                    Getting Started with Basics    
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Topic to be covered :-
- Introductory Terms and Concepts 
- The Terminal 
- The Linux Filesystem 
- Basic Commands in Linux 
- Finding Yourself with pwd
- Checking Your Login with whoami
- Navigating the Linux Filesystem 
- Getting Help 
- Referencing Manual Pages with man
- Finding Stuff 
- Searching with locate 
- Finding Binaries with whereis 
- Finding Binaries in the PATH Variable with which 
- Performing More Powerful Searches with find 
- Filtering with grep
- Modifying Files and Directories 
- Creating Files
- Creating a Directory 
- Copying a File
- Renaming a File
- Contents in Detail
- Removing a File
- Removing a Directory 
- Exercises
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Important note - 
*My user name is "KALI" in "KALI LINUX"*
*So my return of command and run the command based on it*
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Introductory Terms and Concepts
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Binaries - 
This term refers to files that can be executed, similar to executables in Windows. Binaries generally reside in the /usr/bin or usr/sbin directory
and include utilities such as ps, cat, ls, and ifconfig .

#### Case sensitivity -
Unlike Windows, the Linux filesystem is case sensitive. This means that Desktop is different from desktop, which is different from DeskTop.
Each of these would represent a different file or directory name. Many people coming from a Windows environment can find this frustrating. 
If you get the error message “File or directory not found” and you are sure the file or directory exists, you probably need to check your case.

#### Directory -
This is the same as a folder in Windows. A directory provides a way of organizing files, usually in a hierarchical manner.

#### Home -
Each user has their own /home directory, and this is generally where files you create will be saved by default.

#### Kali -
Kali Linux is a distribution of Linux specifically designed for penetration testing. It has hundreds of tools preinstalled, saving you the hours 
it would take to download and install them yourself.

#### root -
Like nearly every operating system, Linux has an administrator (or superuser) account, designed for use by a trusted person who can do 
nearly anything on the system. This would include such things as reconfiguring the system, adding users, and changing passwords. In Linux, that account is called root. 
As a hacker or pentester, you will often use the root account to give yourself control over the system. In fact, many hacker tools require that you use the root account.

#### Script-
This is a series of commands run in an interpretive environ￾ment that converts each line to source code. Many hacking tools are simply scripts. 
Scripts can be run with the bash interpreter or any of the other scripting language interpreters, such as Python, Perl, or Ruby. 
Python is currently the most popular interpreter among hackers.

#### Shell -
This is an environment and interpreter for running commands in Linux. The most widely used shell is bash, which stands for Bourne￾again shell,
but other popular shells include the C shell and Z shell. I will be using the bash shell exclusively in this book.

#### Terminal -
This is a command line interface (CLI).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### The Linux Filesystem
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
```text
/
├── /root
│   └── Superuser's home directory
│
├── /boot
│   └── Kernel image
│
├── /etc
│   └── System configuration files
│
├── /home
│   └── User directories
│
├── /mnt
│   └── General-purpose mount point
│
├── /proc
│   └── View of internal kernel data
│
├── /dev
│   └── Special device files
│
├── /bin
│   └── Binaries
│
├── /sbin
│   └── Binaries
│
├── /lib
│   └── Libraries
│
└── /usr
    ├── /usr/bin
    │   └── More binaries
    │
    └── /usr/lib
        └── More libraries
```
**/root** The home directory of the all-powerful root user

**/etc** Generally contains the Linux configuration files—files that control when and how programs start up

**/home** The user’s home directory

**/mnt** Where other filesystems are attached or mounted to the filesystem

**/media** Where CDs and USB devices are usually attached or mounted to the filesystem

**/bin** Where application binaries (the equivalent of executables in Microsoft Windows or applications in macOS) reside

**/lib** Where you’ll find libraries (shared programs that are similar to Windows DLLs)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Basics Commands In Linux
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Finding yourself with pwd**
```bash
kali>pwd
```
*Return:-* 
```text
home/kali
```
*________________________________________________________________________________________________________________________________________________________________*

**Checking Your Login with whoami**
```bash
kali>whoami
```
*Return:-* 
```text
kali
```


















