linux
1. leading os on servers, embeded systems, mobile systems(Android).
2. most widely-used platform for open source software devlopment.
3. secure and stable.
4. runs on CLI but many distributions support GULs as well.

shell<kernel<hardware resource
-kernel:core of os that controls and communicates with hardware resource.
-shell: interface that allows users to communicate with kernel.
Users runs applications and give commands thtough shell.

CLI
Have to remember commands.
Relatively fast Scripts enable automation and records Basic environment for developers.

GUL
Easy to use and Intuitive.
Relatively slow.
Manual labors required for repetitive tasks For daily users.

1. pwd: shows the current path in a hierarchical directory.
2. cd: change directory.
3. ls: list files and directories.
   ls /bin: list the files in the /bin directory.
   ls -1: list the files in the working directory in long format.
   ls -1 /etc/bin: list the files in the /bin directory and the /etc directory in long format.
   ls -la ..: list all files in the parent of the working directory in long format.


5. arguments:
[directory name]
/ root
. current directory
.. upper-level directory
~ home of current user 
/[directory name]: absolute path
./[directory name]: relative path 
../[directory name]: relative path

6. options:
-l show detailed information (long format) -lh same as above, but size in units
7. clear: clear the shell command.
8. cp: copy files and directories.
   cp file1 file2: copies the contents of file1 into file2 dose not exist, it is created;otherwide, file2 is allently overwritten with the contents of file1.
   cp -1 file1 file2: lke above however, sonce the "-1"option is specified, if file2 exists, the user before ot is overwritten with the contents of file1.
   cp file1 dir1: copy the contents of file1(into a file named file1)inside the directory dir1
   cp -a dir1 dir2: copy the contents of the directory dir1. if directory dir2 does not exist, ot is created. Otherwise, it creates a directorynamed dir1 within directory dir2.

9. mv: move files and directories or rename them.
   mv file1 file2: If file2 does not eists, then file1 is renamed file2. If file2 exists, its contexts are silently replaced with the contexts of file1.
   mv -i file1 file2: Like above however, since the "-I" (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents or met.
   mv filel file2 dir1: The files file1 and file2 are moved to directory dir1. If dir1 does not exist, mv will exit with an error.
   mv dir1 dir2: It dir2 does not exist, then dir2 is renamed dir2. If dir2 exists, the directory dir1 is moved within directory dir2.

10. rm: delete files and directories.
   rm file1 file2: Delete file1 and file2.
   rm -i file1 file2: Like above however. since the "-¡" (interactive) option is specified. the user is promoted before each file is deleted.
   -r dir1 dir2: Directories dir1 and dir2 are deleted along with all of their contents.
11. mkdir: make a new directory.
12. *: All filenames.
13. g*: All filenames that begin with the character "g".
14. b*.txt: All filenames that begin with the character "b" and end wih the characters ".txt".
15. Data???: Any filename that begins with the characters "Data" followed by exactly 3 more characters.
16. cp *.txt text files: Copy all files in the current working directory with names ending with the characters ".txt" to an existing directory named text_files.
17. mv diri ../*.bak dir2: Move the subdirectory dir1 and all the files ending in "bak" in the current working directory's parent directory to an existing directory named dir2.
18. rm *\~: Delete all files in the current working directory that end with the character "\~". Some applications create backup files using this naming scheme. Using this command will clean them out of a directory.
19. help command 1) help 2)man
20. exit: exit command shell.

