1. Check your current working directory.
(pwd)
/home/dinesh-khade/Linux/learning_Linux/Linux-Foundation-practices

2. List all files in your home directory.
(ls)
dinesh-khade

3. List files with detailed information.
(ls -l)
total 8
-rw-rw-r-- 1 dinesh-khade dinesh-khade 431 Dec 20 11:56 nevigation-and-directory.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade 177 Dec 20 22:10 solutions.md

4. List all files including hidden files.
(ls -la)
total 16
drwxrwxr-x 2 dinesh-khade dinesh-khade 4096 Dec 20 22:12 .
drwxrwxr-x 4 dinesh-khade dinesh-khade 4096 Dec 20 11:22 ..
-rw-rw-r-- 1 dinesh-khade dinesh-khade  431 Dec 20 11:56 nevigation-and-directory.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade  388 Dec 20 22:12 solutions.md


5. Create a directory named linux_practice.
(mkdir linux_practice)
linux_practice


6. Create nested directories devops/day1.
(mkdir -p devops/day1 >> solutions.md)
devops/day1

7. Movie into the linux_practice directory.
(linux_practice)
linux_practice

8. Go back to the parent directory.
(cd.. / cd../.. /cd -)

9. Go directly to your home directory.
(cd ~)

10. clear the terminal screen.
(clear)
