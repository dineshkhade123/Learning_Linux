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


11. Create nested directories day1/day2/day3.
(mkdir -vp day1/day2/day3)
mkdir: created directory 'day1'
mkdir: created directory 'day1/day2'
mkdir: created directory 'day1/day2/day3' 

12. Enter the day3 directory.
(cd)


13. Display only directory names.
(ls -d */)
day1/

14.  Create a directory with spaces in name.
(mkdir "my repo")
'my repo'


15. Count number of files in a directory.
(find . -type f | wc -l)

 22

16. Sort files by time.
(ls -lt)
total 12
-rw-rw-r-- 1 dinesh-khade dinesh-khade 1573 Dec 21 14:14 solutions.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file10.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file11.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file12.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file13.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file14.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file15.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file16.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file17.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file18.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file19.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file1.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file20.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file2.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file3.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file4.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file5.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file6.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file7.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file8.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file9.txt
drwxrwxr-x 3 dinesh-khade dinesh-khade 4096 Dec 21 11:24 day1
-rw-rw-r-- 1 dinesh-khade dinesh-khade  808 Dec 21 11:16 nevigation-and-directory.md


17. Sort files by size.
(ls -lh)
total 12K
drwxrwxr-x 3 dinesh-khade dinesh-khade 4.0K Dec 21 11:24 day1
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file10.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file11.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file12.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file13.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file14.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file15.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file16.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file17.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file18.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file19.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file1.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file20.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file2.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file3.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file4.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file5.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file6.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file7.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file8.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 21 13:42 file9.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade  808 Dec 21 11:16 nevigation-and-directory.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade 3.2K Dec 21 14:22 solutions.md


18. Navigate using absolute path.
(start with root directory)
/home/dinesh-khade/Linux/learning_Linux/Linux-Foundation-practices


19. Delete an empty directory.
(cd .. / cd ../dirname)

20.  Delete an empty directory.
(mkdir dirname)


21. Delete a directory recursively.
(rm -r dirname)

