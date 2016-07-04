# HackCloudDrive
Use a shell to change the content of files.

#Why I write this shell
This is a shell to chane the content of files,I write this in order to change the Hash of files in *** field.

# reference
[scripts-to-traverse-folder-recursively]( http://yejinxin.github.io/scripts-to-traverse-folder-recursively/)

# how to use
1. Download the MagicShell shell 
2. chmod +x MagicShell
3. The parameter input can be 
	1. 	a directory
	 
	 ~~~ 
	 ./MagicShell /Users/Downloads/testHash
	 ~~~
	 
	2. directories 
	
		~~~
		./MagicShell /Users/Downloads/testHashDirectory1 ./MagicShell /Users/Downloads/testHashDirectory2
		~~~
	3. a single file 
	
		~~~ 
		./MagicShell   /Users/Downloads/testHash/		file1.txt
		~~~
	4. files 
	
		~~~
		./MagicShell   /Users/Downloads/testHash/file1.txt /Users/Downloads/testHash/file2.txt
		~~~
 		

#at last
Those who do not understand UNIX are condemned to reinvent it, poorly.

—Henry Spencer
