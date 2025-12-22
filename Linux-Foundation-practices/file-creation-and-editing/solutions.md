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


