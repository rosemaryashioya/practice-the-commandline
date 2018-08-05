# practice-the-commandline
Commandline practice Exercise

1. If you're not already there, navigate to the home directory.
2. Print your location to the screen to make sure you're in the right spot.
```
kube@kube:~$ pwd 
/home/kube
```

3. List the contents of the Home directory to the terminal.
```
kube@kube:~$ ls -la
total 120
drwxr-xr-x 17 kube kube  4096 Hag  5 06:56 .
drwxr-xr-x  4 root root  4096 Ado 31 06:33 ..
drwxr-x---  2 kube kube  4096 Wax 22 21:45 .android
drwxrwxr-x  9 kube kube  4096 Hag  2 17:07 .atom
-rw-------  1 kube kube 20445 Hag  4 15:48 .bash_history
-rw-r--r--  1 kube kube   220 Wax 16 22:26 .bash_logout
-rw-r--r--  1 kube kube  3771 Wax 16 22:26 .bashrc
drwx------ 18 kube kube  4096 Hag  4 17:44 .cache
drwx------  3 kube kube  4096 Hag  3 15:17 .compiz
drwx------ 19 kube kube  4096 Hag  5 06:50 .config
drwxr-xr-x  2 kube kube  4096 Hag  5 07:18 Desktop
drwx------  2 kube kube  4096 Hag  4 08:16 .gconf
drwxrwxr-x  8 kube kube  4096 Hag  4 12:31 .git
-rw-rw-r--  1 kube kube    48 Hag  3 10:52 .gitconfig
drwx------  3 kube kube  4096 Ado 31 10:27 .gnome
drwx------  3 kube kube  4096 Hag  5 06:50 .gnupg
drwxr-xr-x  2 kube kube  4096 Hag  4 18:51 .hplip
-rw-------  1 kube kube  1860 Hag  5 06:50 .ICEauthority
drwx------  3 kube kube  4096 Wax 16 22:49 .local
drwxr-xr-x  5 kube kube  4096 Hag  3 13:28 .mozilla
drwxrwxr-x  2 kube kube  4096 Hag  1 21:49 .nano
drwx------  3 kube kube  4096 Hag  3 12:22 .pki
-rw-------  1 kube kube    49 Hag  5 06:50 .Xauthority
-rw-------  1 kube kube    82 Hag  5 06:50 .xsession-errors
-rw-------  1 kube kube  1230 Hag  4 19:36 .xsession-errors.old
```

4. Navigate to the Desktop directory.
```
kube@kube:~$ cd Desktop/
```

5. Create a directory named test.
```
kube@kube:~/Desktop$ mkdir test
```

6. Navigate to the test directory.
```
kube@kube:~/Desktop$ cd test/
```

7. Create a file named file1.html.
```
kube@kube:~/Desktop/test$ touch file1.html
```

8. Create two more files named file2.html and file3.html. (Here's a tip: you can create two files with a single command! Simply separate the two file names with a space: $ touch file2.html file3.html)
```
kube@kube:~/Desktop/test$ touch file2.html file3.html
kube@kube:~/Desktop/test$ ls
file1.html  file2.html  file3.html
```

9. Create a directory named first-directory.
```
kube@kube:~/Desktop/test$ mkdir first-directory
```

10. Move file1.html into first-directory.
```
kube@kube:~/Desktop/test$ mv file1.html first-directory/
```

11. Copy file2.html and name the copy file4.html.
```
kube@kube:~/Desktop/test$ cp file2.html file4.html
kube@kube:~/Desktop/test$ ls
file2.html  file3.html  file4.html  first-directory
```

12. Rename file3.html to third-file.html.
```
kube@kube:~/Desktop/test$ mv file3.html third-file.html
kube@kube:~/Desktop/test$ ls
file2.html  file4.html  first-directory  third-file.html
```

13. Navigate into first-directory.
```
kube@kube:~/Desktop/test$ cd first-directory/
```

14. Delete file1.html.
```
kube@kube:~/Desktop/test/first-directory$ rm -f file1.html 
```

15. Navigate up one directory so that you are back in test.
```
kube@kube:~/Desktop/test/first-directory$ cd ..
```

16. Print your location to verify that you are back in test.
```
kube@kube:~/Desktop/test$ pwd
/home/kube/Desktop/test
```

17. Delete first-directory.
```
kube@kube:~/Desktop/test$ rm -rf first-directory/
```

18. List the contents to the page to make sure that first-directory was successfully deleted.
```
kube@kube:~/Desktop/test$ ls
file2.html  file4.html  third-file.html
```

19. Clear the terminal screen.
```
kube@kube:~/Desktop/test$ clear
```
