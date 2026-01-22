# Linux-Assignment-Tutedude-

1. Creating and Renaming Files/Directories
# Create a directory named test_dir using mkdir.
mkdir = to make a new directory we use this command. 
•	Command = mkdir test_dir
 
# Inside test_dir, create an empty file called example.txt.
Using touch command we have created new file in test_dir
touch = we use this command for create a new file in directory. We can create .py, .txt , etc.,
•	Command = touch testdir/example.txt

 
# Rename example.txt to renamed_example.txt using mv
We have renamed the file as renamed_example.txt using mv command
mv = this command is used for move the file so in the below snapshot against the mv we give the path and name in source and target field.
•	Command = mv test_dir/example.txt test_dir/renamed_example.txt
 


2. Viewing File Contents
Use cat to display the contents of /etc/passwd.
•	Command = cat /etc/passwd
 
# Display only the first 5 lines of /etc/passwd using head.
Using head command I have fetch first five lines. In the below snapshot I have used the -n 5 for fetch only five rows by default it returning 10 rows
•	Command = head -n 5 /etc/passwd
 
# Display only the last 5 lines of /etc/passwd using tail.
For last 5 lines I have used the tail command to get result. In the below snapshot I have used the -n 5 for fetch only five rows by default it returning 10 rows
•	Command = tail -n 5 /etc/passwd

 
3.Searching for Patterns
#Use grep to find all lines containing the word "root" in /etc/passwd.
To find the word in file we used the grep command.
•	Command = grep “root” /etc/passwd

  
4. Zipping and Unzipping
#Compress the test_dir directory into a file named test_dir.zip using zip.
I have used the zip command for zipped the directory.
-r it is used for to include everything which is in that directory.
•	Command = zip -r test_dir.zip test_dir

 
#Unzip test_dir.zip into a new directory named unzipped_dir.
First, I have removed existing directory and then used unzipped commands for unzip it. In below snapshot, using the unzip command its successfully.
•	Command = unzip test_dir.zip
 

5. Downloading Files
#Use wget to download a file from a URL (e.g., https://example.com/sample.txt).
We have download a file using wget command.
•	Command = wget https://example.com/sample.txt
 

6. Changing Permissions
#Create a file named secure.txt and change its permissions to read-only for everyone using chmod.
I have used the touch command for crate the file. And for set the permission I have used the chmod 444 which is used for only read access permission.
•	Command = chmod 444 secure.txt
 

7. Working with Environment Variables
#Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!".
In the below snapshot using the export command I have created new variable as my_
var. post it to check the variable is created or not I have used the echo command. 
•	Command = export my_var=”Hello Linux!”
 


