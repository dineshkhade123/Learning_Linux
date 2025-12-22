1. Create an empty file named file1.txt.

touch file1.txt


2. Create multiple files in one command.

touch file{1..10}.txt / touch file1.txt file2.txt file3.txt file4.txt file4.txt


3. Create a file with today’s date.

touch today_$(date +%Y-%m-%d).txt


4. Write text to a file using redirection.

echo "hello this is todays date" > today.txt


5. Append text to an existing file.

echo "hello dosto" >> today.txt


6. Overwrite file content.

echo "Today" > demo.txt


7. Create a file inside a directory.

mkdir dk
touch dk/dkfile.txt 


8. Rename a file.

cd dk
mv dkfile.txt myfile.txt


9. Copy a file.

cp myfile.txt / cp myfile.txt newfile.txt


10. Move a file to another directory.

mkdir dk1
mv myfile.txt dk1


11. Create a backup of a file.

cp solution.txt solution.bak
tar -czvf solution.txt 2solutions.bak


12. Create a file with numbers as content.

echo "12345678910" > number.txt


13. Create a hidden file.

 touch .hidden.txt
 ls -a


14. Create files using a loop (basic idea).

touch loop.sh
for name in dev qa tester ; do echo "this is file" > my$name.txt ; done
ls
mydev myqa mytester

15. Check file type.

ls -l / ls -a / 
total 56
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 22 12:21 2solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade   40 Dec 22 12:09 backup.txt
drwxrwxr-x 2 dinesh-khade dinesh-khade 4096 Dec 22 11:40 demo
-rw-rw-r-- 1 dinesh-khade dinesh-khade  699 Dec 21 21:57 file-creation_and_editing.md
-rwxrwxr-x 1 dinesh-khade dinesh-khade  130 Dec 22 13:19 loop.sh
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mydev.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 myqa.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mytesterl.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:29 number-file.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:34 number-file.txtls
-rw-rw-r-- 1 dinesh-khade dinesh-khade   14 Dec 22 12:34 numbers.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    1 Dec 22 13:31 solution.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade  898 Dec 22 12:19 solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade 1155 Dec 22 13:32 solutions.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade  129 Dec 22 12:21 solution.txt


16. Display file size.

ls -lt 
total 56K
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 22 12:21 2solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade   40 Dec 22 12:09 backup.txt
drwxrwxr-x 2 dinesh-khade dinesh-khade 4.0K Dec 22 11:40 demo
-rw-rw-r-- 1 dinesh-khade dinesh-khade  699 Dec 21 21:57 file-creation_and_editing.md
-rwxrwxr-x 1 dinesh-khade dinesh-khade  130 Dec 22 13:19 loop.sh
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mydev.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 myqa.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mytesterl.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:29 number-file.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:34 number-file.txtls
-rw-rw-r-- 1 dinesh-khade dinesh-khade   14 Dec 22 12:34 numbers.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    1 Dec 22 13:31 solution.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade  898 Dec 22 12:19 solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade 2.2K Dec 22 13:34 solutions.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade  129 Dec 22 12:21 solution.txt
17. Display last modified time.
total 56
-rw-rw-r-- 1 dinesh-khade dinesh-khade 3339 Dec 22 13:36 solutions.md
-rw-rw-r-- 1 dinesh-khade dinesh-khade    1 Dec 22 13:31 solution.md
-rwxrwxr-x 1 dinesh-khade dinesh-khade  130 Dec 22 13:19 loop.sh
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mydev.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 myqa.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   13 Dec 22 13:17 mytesterl.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:34 number-file.txtls
-rw-rw-r-- 1 dinesh-khade dinesh-khade   14 Dec 22 12:34 numbers.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade   18 Dec 22 12:29 number-file.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade  129 Dec 22 12:21 solution.txt
-rw-rw-r-- 1 dinesh-khade dinesh-khade    0 Dec 22 12:21 2solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade  898 Dec 22 12:19 solutions.bak
-rw-rw-r-- 1 dinesh-khade dinesh-khade   40 Dec 22 12:09 backup.txt
drwxrwxr-x 2 dinesh-khade dinesh-khade 4096 Dec 22 11:40 demo
-rw-rw-r-- 1 dinesh-khade dinesh-khade  699 Dec 21 21:57 file-creation_and_editing.md


18. Create a file and add content in one command.

echo hello > file.txt


19. Edit file using terminal editor (concept).


vim file.txt

20. Delete a file safely.

rm -f file.txt

#happylearning 
