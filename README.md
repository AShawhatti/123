conda activate icm-devops
Now you're in a virtual environment where you can run Python or install packages.

🔹 Step 3: Run Python
Once the environment is active:

python
You’ll enter the Python interactive shell:


>>> print("Hello from Miniconda!")
Hello from Miniconda!

exit()
🔹 Step 4: Run Python Scripts
If you have a .py file:

python my_script.py
Or run a one-liner:


python -c "print('Hi from conda CLI!')"


✅ Common CLI Editors
nano my_script.py
Inside nano:
Type or edit your code.

Save: Press Ctrl + O then Enter

Exit: Press Ctrl + X



🔹 3. Create a New File from CLI

nano new_script.py
You can create and start typing immediately.

🔹 4. Open File with GUI Editor from CLI
If you're using VS Code, and it’s installed:

code my_script.py
If you're on Windows:











(base) Adam@ubuntu:~$ sudo apt update
[sudo] password for Adam: 
0% [Working]^C
(base) Adam@ubuntu:~$ ls -l /home
total 4
drwxr-x--- 24 Adam Adam 4096 Jun 16 21:43 Adam
(base) Adam@ubuntu:~$ sudo -s
root@ubuntu:/home/Adam# mysql -u root -p
Enter password: 
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 8
Server version: 8.0.42 MySQL Community Server - GPL

Copyright (c) 2000, 2025, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> Show databases;
+--------------------+
| Database           |
+--------------------+
| ICM                |
| information_schema |
| mysql              |
| performance_schema |
| sys                |
+--------------------+
5 rows in set (0.01 sec)

mysql> use ICM;
Database changed
mysql> Show tables;
Empty set (0.00 sec)

mysql> ^C
mysql> exit
Bye
root@ubuntu:/home/Adam# pwd
/home/Adam
root@ubuntu:/home/Adam# mkdir ICM2025
root@ubuntu:/home/Adam# pwd
/home/Adam
root@ubuntu:/home/Adam# cd /home/Adam/ICM2025
root@ubuntu:/home/Adam/ICM2025# ls
root@ubuntu:/home/Adam/ICM2025# touch ICM2.txt
root@ubuntu:/home/Adam/ICM2025# ls
ICM2.txt
root@ubuntu:/home/Adam/ICM2025# cd ..
root@ubuntu:/home/Adam# ls
Desktop    Downloads  icm-devops      miniconda3  Pictures     Public  Templates
Documents  ICM2025    kubectl.sha256  Music       Presntation  snap    Videos
root@ubuntu:/home/Adam# cd /home/Adam/ICM2025
root@ubuntu:/home/Adam/ICM2025# nano ICM2.txt
root@ubuntu:/home/Adam/ICM2025# ls
ICM2.txt
root@ubuntu:/home/Adam/ICM2025# cat ICM2.txt
This is my first linux file 
root@ubuntu:/home/Adam/ICM2025# nano ICM2.txt
root@ubuntu:/home/Adam/ICM2025# cat ICM2.txt
This is my first linux file 
ctrl-O is to write out the text to the file.
ctrl-X is to exit the text file.
ctrl-K is to cut.
ctrl-\ is to replace.
ctrl-U is to paste.


root@ubuntu:/home/Adam/ICM2025# cd..
cd..: command not found
root@ubuntu:/home/Adam/ICM2025# cd ..
root@ubuntu:/home/Adam# cd /home/Adam/Presntation
root@ubuntu:/home/Adam/Presntation# ls
file.txt  pyth.py
root@ubuntu:/home/Adam/Presntation# pwd
/home/Adam/Presntation
root@ubuntu:/home/Adam/Presntation# nano pyth.py
root@ubuntu:/home/Adam/Presntation# python pyth.py
Command 'python' not found, did you mean:
  command 'python3' from deb python3
  command 'python' from deb python-is-python3
root@ubuntu:/home/Adam/Presntation# python3 pyth.py
helloWorld
root@ubuntu:/home/Adam/Presntation# cat pyth.py
print("helloWorld")


root@ubuntu:/home/Adam/Presntation# python3
Python 3.12.3 (main, Feb  4 2025, 14:48:35) [GCC 13.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("hello world")
hello world
>>> 
KeyboardInterrupt
>>> exit()
root@ubuntu:/home/Adam/Presntation# nano file.txt
root@ubuntu:/home/Adam/Presntation# touch ICM3.txt
root@ubuntu:/home/Adam/Presntation# ps auxf | xclip -selection clipboard
Command 'xclip' not found, but can be installed with:
apt install xclip
root@ubuntu:/home/Adam/Presntation# apt install xclip
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libcgi-fast-perl libcgi-pm-perl libevent-core-2.1-7t64 libevent-pthreads-2.1-7t64 libfcgi-bin
  libfcgi-perl libfcgi0t64 libhtml-template-perl libprotobuf-lite32t64
Use 'apt autoremove' to remove them.
The following NEW packages will be installed:
  xclip
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 17.6 kB of archives.
After this operation, 54.3 kB of additional disk space will be used.
Get:1 http://us.archive.ubuntu.com/ubuntu noble/universe amd64 xclip amd64 0.13-3 [17.6 kB]
Fetched 17.6 kB in 1s (30.6 kB/s)
Selecting previously unselected package xclip.
(Reading database ... 156527 files and directories currently installed.)
Preparing to unpack .../xclip_0.13-3_amd64.deb ...
Unpacking xclip (0.13-3) ...
Setting up xclip (0.13-3) ...
Processing triggers for man-db (2.12.0-4build2) ...
root@ubuntu:/home/Adam/Presntation# ps auxf | xclip -selection clipboard
root@ubuntu:/home/Adam/Presntation# ls
file.txt  ICM3.txt  pyth.py
root@ubuntu:/home/Adam/Presntation# 

