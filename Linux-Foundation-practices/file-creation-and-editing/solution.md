1. Create an empty file named file1.txt.

  touch file.1txt


2. Create multiple files in one command.

touch myfile{1..10}.txt


3. Create a file with today’s date.

touch demo_$(date +%Y-%m-%d)


4. Write text to a file using redirection.

echo "my name is Dinesh" > myintro.txt


5. Append text to an existing file.

echo "i am learning Devops" >> myintro.txt


6. Overwrite file content.

echo "my name is Dinesh Khade" > myintro.txt
