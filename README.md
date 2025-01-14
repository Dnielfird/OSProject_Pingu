# OSProject Running Containers for Application Development

Group Name: __Pingu__. 

Section: __3__. 

Team Mates:
1. __Sharifah Anis Maisarah binti Shaik Fauzi__ and __2126344__
2. __Nabihah binti Sazli__ and __2121604__
3. __Adam bin Othman__ and __2127317__
4. __Muhammad Danniel Firdaus bin Abdul Haizul Faisal__ and __2127967__

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** __https://github.com/Dnielfird/OSProject_Pingu__.
2. How many files and folders are in this repository. ***(1 mark)*** __1 File and 1 folder__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Ubuntu Linux__.
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** __4GB RAM, 32GB, 2-core and 16GB RAm, 32GB, 4-core__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** __Because it can update in the codespace cloud and do not lost it so it can work together__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ pwd
/workspaces/OSProject_Pingu
```
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```
3. Run the command **df** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 13636900  17516684  44% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 22956564   7325228  76% /vscode
/dev/loop3      32847680 13636900  17516684  44% /workspaces
/dev/sda1       46127956      252  43752128   1% /tmp
```
4. Run the command **du** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ du
1972    ./images
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
8       ./.git/info
4       ./.git/branches
8       ./.git/refs/heads
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
4       ./.git/refs/tags
28      ./.git/refs
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/objects/e7
8       ./.git/objects/f6
8       ./.git/objects/fd
8       ./.git/objects/04
8       ./.git/objects/62
12      ./.git/objects/b5
8       ./.git/objects/cb
8       ./.git/objects/d8
8       ./.git/objects/c3
12      ./.git/objects/92
8       ./.git/objects/47
8       ./.git/objects/3f
8       ./.git/objects/1b
8       ./.git/objects/24
12      ./.git/objects/1c
8       ./.git/objects/fa
8       ./.git/objects/0d
4       ./.git/objects/info
8       ./.git/objects/0b
12      ./.git/objects/ff
8       ./.git/objects/e9
1820    ./.git/objects/pack
8       ./.git/objects/4b
8       ./.git/objects/83
8       ./.git/objects/cd
12      ./.git/objects/44
8       ./.git/objects/86
12      ./.git/objects/64
12      ./.git/objects/17
8       ./.git/objects/b2
8       ./.git/objects/7b
12      ./.git/objects/3d
8       ./.git/objects/58
8       ./.git/objects/49
8       ./.git/objects/b6
8       ./.git/objects/ab
12      ./.git/objects/14
12      ./.git/objects/d2
12      ./.git/objects/73
12      ./.git/objects/60
8       ./.git/objects/96
16      ./.git/objects/fb
8       ./.git/objects/4f
12      ./.git/objects/af
8       ./.git/objects/71
8       ./.git/objects/a3
12      ./.git/objects/70
8       ./.git/objects/4a
8       ./.git/objects/fc
8       ./.git/objects/fe
8       ./.git/objects/81
8       ./.git/objects/52
8       ./.git/objects/b9
8       ./.git/objects/c6
8       ./.git/objects/93
8       ./.git/objects/91
12      ./.git/objects/72
8       ./.git/objects/20
8       ./.git/objects/a6
12      ./.git/objects/2e
8       ./.git/objects/74
8       ./.git/objects/f2
2380    ./.git/objects
64      ./.git/hooks
2556    ./.git
4548    .
```
5. Run the command **ls** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ ls
README.md  images
```
6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 Jan 31 13:51 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 31 13:51 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 31 13:57 .git
16 -rw-rw-rw-  1 codespace root 15694 Jan 31 14:07 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jan 31 13:51 images
```
7. Run the command **free -h** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.6Gi       153Mi       1.0Mi       6.0Gi       5.8Gi
Swap:            0B          0B          0B
```
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3168.131
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.87
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3168.615
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.87
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
```bash
top - 14:29:53 up 46 min,  0 users,  load average: 0.41, 0.38, 0.33
Tasks:  19 total,   1 running,  18 sleeping,   0 stopped,   0 zombie
%Cpu(s):  2.9 us,  3.9 sy,  0.0 ni, 93.1 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7930.0 total,    153.1 free,   1701.7 used,   6075.2 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   5912.0 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                                                                                                                       
   2111 codespa+  20   0   21.1g 333896  46336 S   2.0   4.1   0:57.94 node                                                                                                                                                                                          
   2775 codespa+  20   0  670144  65692  39040 S   0.3   0.8   0:02.42 node                                                                                                                                                                                          
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.06 docker-init                                                                                                                                                                                   
      7 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.01 sleep                                                                                                                                                                                         
     54 root      20   0   12192   3480   2560 S   0.0   0.0   0:00.00 sshd                                                                                                                                                                                          
    778 root      20   0 1463336  84296  49792 S   0.0   1.0   0:00.28 dockerd                                                                                                                                                                                       
    786 root      20   0 1208944  52856  30336 S   0.0   0.7   0:00.52 containerd                                                                                                                                                                                    
   1492 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   1518 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   2046 codespa+  20   0    2624   1536   1536 S   0.0   0.0   0:00.01 sh                                                                                                                                                                                            
   2055 codespa+  20   0  981040 121676  42624 S   0.0   1.5   0:07.64 node                                                                                                                                                                                          
   2173 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   2182 codespa+  20   0  849188  56808  38528 S   0.0   0.7   0:00.34 node                                                                                                                                                                                          
   2226 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   2811 codespa+  20   0  617096  70752  38272 S   0.0   0.9   0:04.15 node                                                                                                                                                                                          
   3694 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   3738 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                                                                                                                            
   3911 codespa+  20   0   16628  11520   3328 S   0.0   0.1   0:00.17 bash                                                                                                                                                                                          
  19173 codespa+  20   0   10864   3584   3072 R   0.0   0.0   0:00.00 top   
```
10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ uname -a
Linux codespaces-6f077b 6.2.0-1018-azure #18~22.04.1-Ubuntu SMP Tue Nov 21 19:25:02 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. ***(1 mark)*** __153Mi__.
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.6Gi       153Mi       1.0Mi       6.0Gi       5.8Gi
Swap:            0B          0B          0B
```
12. What is the available disk space mounted on /workspace. ***(1 mark)*** __32G__
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ df -h
Filesystem      Size  Used Avail Use% Mounted on
overlay          32G   14G   17G  44% /
tmpfs            64M     0   64M   0% /dev
shm              64M  8.0K   64M   1% /dev/shm
/dev/root        29G   22G  7.1G  76% /vscode
/dev/loop3       32G   14G   17G  44% /workspaces
/dev/sda1        44G  344K   42G   1% /tmp
```
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** __The Ubntu Linux version is 20.04 and hardware architecture is x86_64__
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ lsb_release -a
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 20.04.6 LTS
Release:        20.04
Codename:       focal
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ uname -m
x86_64
```
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** __The ls command in Linux is used for listing files and directories, providing a basic output with just names. On the other hand, ls -asl offers a more detailed listing, including file permissions, owner, group, size, and modification date__.
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ ls
README.md  images
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ ls -asl
total 40
 4 drwxrwxrwx+ 4 codespace root  4096 Jan 31 13:51 .
 4 drwxr-xrwx+ 5 codespace root  4096 Jan 31 13:51 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jan 31 13:57 .git
24 -rw-rw-rw-  1 codespace root 22286 Jan 31 14:24 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 Jan 31 13:51 images
```
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** __2560 4K pages__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** __3168.131 MHz__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** __Codespace because it consumes 2.0% CPU and 4.1% Memory__.
```bash
    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                                                                                                                       
   2111 codespa+  20   0   21.1g 333896  46336 S   2.0   4.1   0:57.94 node  
```
## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Happening in the terminal***
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
1b13d4e1a46e: Pull complete 
Digest: sha256:b16cef8cbcb20935c0f052e37fc3d38dc92bfec0bcfb894c328547f81e932d67
Status: Downloaded newer image for debian:latest
docker.io/library/debian:latest
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker run --detach -it debian
0b3bb56cc36c775e3b9f461841858af53fb8ced7ff841dfecfab9a4be29423e6
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
0b3bb56cc36c   debian    "bash"    50 seconds ago   Up 48 seconds             youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker exec -i -t youthful_moser /bin/bash
root@0b3bb56cc36c:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [52.1 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8787 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [12.7 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [135 kB]
Fetched 9186 kB in 1s (8862 kB/s)                         
Reading package lists... Done
root@0b3bb56cc36c:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 2 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (21.0 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6098 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u3) ...
root@0b3bb56cc36c:/# cd /root
root@0b3bb56cc36c:~# nano helloworld.txt
root@0b3bb56cc36c:~# exit
exit
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
0b3bb56cc36c   debian    "bash"    3 minutes ago   Up 3 minutes             youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker stop youthful_moser
youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                       PORTS     NAMES
0b3bb56cc36c   debian    "bash"    4 minutes ago   Exited (137) 8 seconds ago             youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker restart youthful_moser
youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker stop youthful_moser
youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                       PORTS     NAMES
0b3bb56cc36c   debian    "bash"    5 minutes ago   Exited (137) 6 seconds ago             youthful_moser
@Dnielfird ➜ /workspaces/OSProject_Pingu (main) $ docker rm youthful_moser
youthful_moser
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** __Files in a container are not persistent by default, but persistence can be achieved using volumes or bind mounts__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** __Yes, we can run multiple instances of Debian Linux or any other containerized application, and each instance operates independently in its isolated environment__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __The user is root and the group is root__.
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu/myroot (main) $ ls -ld
drwxrwxrwx+ 2 root root 4096 Jan 31 15:23 .
```
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```

*** __Yes. The user is codespace __.***

```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu/myroot (main) $ sudo chown -R codespace:codespace myroot
@Dnielfird ➜ /workspaces/OSProject_Pingu/myroot (main) $ ls -l myroot
total 2
drwxrwxrwx+ 2 codespace codespace 4096 Jan 31 15:25 .
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** ***__Permission: drwxrwxrwx+ , User: 1000 , Group: 1000__***
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu/webpage (main) $ docker exec -it wonderful_mcclintock ls -ld /usr/local/apache2/htdocs
drwxrwxrwx+ 2 1000 1000 4096 Jan 31 16:30 /usr/local/apache2/htdocs
```
2. What port is the apache web server running. ***(1 mark)*** 
***__Apache web server is running on port 80.__***

```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu/webpage (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                                   NAMES
68a11a0d607d   httpd     "httpd-foreground"   8 minutes ago    Up 8 minutes    0.0.0.0:8080->80/tcp, :::8080->80/tcp   wonderful_mcclintock
```
3. What port is open for http protocol on the host machine? ***(1 mark)*** ***__The port for http protocol accessible on the host machine at port 8080.__***
```bash
@Dnielfird ➜ /workspaces/OSProject_Pingu/webpage (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS          PORTS                                   NAMES
68a11a0d607d   httpd     "httpd-foreground"   8 minutes ago    Up 8 minutes    0.0.0.0:8080->80/tcp, :::8080->80/tcp   wonderful_mcclintock
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***31 January, 2024***
