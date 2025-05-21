# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
### NAME : G LEKASRI
### REGISTER NUMBER : 212223100025
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:

* Machine with Internet access
* Minimum 4 GB RAM
* Sufficient storage space

## Steps:
1. Download Oracle VM VirtualBox:

    * Visit Oracle VirtualBox Official Site
    * Download installer for your OS (Windows/macOS/Linux).
2. Install Oracle VM VirtualBox (Example: Windows):

    * Launch Installer → Allow Changes → Click Next.
    * Choose Installation Options → Click Next.
    * Accept Network Interface Warning → Click Yes.
    * Click Install.
    * Finish Installation and Launch VirtualBox.
3. Configure VirtualBox:

    * Open VirtualBox.
    * Click New → Name VM → Select Type (Linux/Windows) and Version.
    * Allocate:
        * Minimum 2 GB RAM
        * Create Virtual Hard Disk (20 GB recommended).
    * Start Virtual Machine and provide ISO to install OS.

## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
* Oracle VM VirtualBox Installed
* 4 GB RAM and 20 GB Storage Minimum
* Kali Linux ISO image

## Steps:
1. Download Kali Linux ISO:

    * Visit Kali Linux Official Site
    * Download 64-bit ISO (Installer version).
2. Create a New Virtual Machine:

    * Open VirtualBox → Click New.
    * Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3. Allocate Memory:

    * Minimum 2 GB RAM (recommended 4 GB).
4. Create Virtual Hard Disk:

    * Select VDI (VirtualBox Disk Image).
    * Choose Dynamically allocated.
    * Set Disk size to 20 GB or more.
5. Configure ISO Image:

    * Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6. Start Installation:

    * Boot Virtual Machine → Choose Graphical Install.
    * Set Language, Region, Keyboard.
    * Configure Network → Set Hostname (e.g., kali).
    * Set root password.
    * Disk Partitioning: Use entire disk → All files in one partition.
    * Install System → Install GRUB Bootloader → Finish Installation.
7. Login to Kali Linux:

    * Use root credentials.
8. (Optional) Install Guest Additions:

    * Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
![C 1](https://github.com/user-attachments/assets/a28a3445-e0ce-48cc-8efc-c587cf0ef4fb)

Snapshot 2: Kali Running in Virtual
![C 2](https://github.com/user-attachments/assets/4623f26d-fe72-4992-996c-1ae24cc057fa)

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali

## About Linux:
* Open-source operating system.
* Kernel manages communication between hardware and software.
* Commands are case-sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![C 3](https://github.com/user-attachments/assets/7c76b7eb-fddb-4f63-bea1-ca9ef396175f)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


 ![C 4](https://github.com/user-attachments/assets/652df190-41a3-48f6-b634-028e898cd03f)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![C 5](https://github.com/user-attachments/assets/bd27e042-fc49-4a05-ad6e-990ad7885ecf)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![C 6](https://github.com/user-attachments/assets/559e67f4-4d0d-40b8-8174-230cd673dc7a)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![C 7](https://github.com/user-attachments/assets/67b4872b-fe06-4840-9435-c85fcc14902b)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![C 8](https://github.com/user-attachments/assets/247794bf-eff1-452c-9e73-6dab0cd34c7d)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![C 9](https://github.com/user-attachments/assets/41f01430-d8c6-4e18-b4e0-eea6aeaddd7d)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![C 10](https://github.com/user-attachments/assets/2fa21a69-743f-4cac-bdfb-de933d76a8cd)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![C 11](https://github.com/user-attachments/assets/1c73f0c9-1a55-4754-b4cd-47adef98ecb2)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![C 12](https://github.com/user-attachments/assets/ac7bd285-6f72-411f-8b6c-4bccbb6d3e33)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![C 13](https://github.com/user-attachments/assets/adeab4f1-6839-4eb9-99ee-910abacf09a5)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


![C 14](https://github.com/user-attachments/assets/50a02da3-e34b-469f-860a-ad479eb74c6c)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![C 15](https://github.com/user-attachments/assets/666c5f83-7d5d-4812-b174-0cc8a9bed705)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![C 16](https://github.com/user-attachments/assets/8e734c73-4da9-44de-891b-74ba49cfe091)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![C 17](https://github.com/user-attachments/assets/39272fd0-34d7-4d14-b437-cca5ca8d6c9d)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![C 18](https://github.com/user-attachments/assets/0c2c69cc-46d0-4d76-950a-f1034f2b6edb)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>


![C 19](https://github.com/user-attachments/assets/af836f28-a0bd-4dc5-8fc6-063dc13ae148)


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

![C 20](https://github.com/user-attachments/assets/33955453-19a6-45be-b764-fbaec4e28da9)

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![C 21](https://github.com/user-attachments/assets/cc25dc55-f299-41d8-9599-5f11129bf24f)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![C 22](https://github.com/user-attachments/assets/394c5e44-a452-4b62-a865-90f1bdfcadd6)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![C 23](https://github.com/user-attachments/assets/d7b56d5f-90d2-4243-8471-3fefb7140bcd)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

![C 24](https://github.com/user-attachments/assets/2b8e264d-b6c5-4f2f-a5d5-0834ffd342aa)

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![C 25](https://github.com/user-attachments/assets/1e68f81b-5451-4243-9b90-bcac3852bffa)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![C 26](https://github.com/user-attachments/assets/497dc348-6672-4866-8853-dc902b4e755c)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![C 27](https://github.com/user-attachments/assets/6bf0eb85-1657-4f1b-9548-04119147fd61)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![C 28](https://github.com/user-attachments/assets/9b218823-a09e-44cd-bd92-5009894e961e)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![C 29](https://github.com/user-attachments/assets/e3339e82-5a73-4592-bb08-2e881620fc76)


![C 30](https://github.com/user-attachments/assets/b9781eb2-15c7-4e9c-b19c-2f60163452df)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![C 31](https://github.com/user-attachments/assets/b1682066-9cea-449b-bb97-80f971d47f33)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![C 32](https://github.com/user-attachments/assets/2dc4ef90-24e2-4ea4-b6f4-d4333b8410a2)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![C 33](https://github.com/user-attachments/assets/c7fc5eec-b9cb-4fc9-a42b-8a9cecc5171a)

![C 34](https://github.com/user-attachments/assets/cb9be530-fcba-4c64-b075-116da9c06e7b)




## Result:

Thus, the execution of various Linux commands is executed successfully using Kali Linux.
