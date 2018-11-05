
##### Learned what a filepath is, and the case-sensitive nature of CLI ('command-line interface')
where to find certain file in doc. 

e/t is case sensitive 

##### Using modifiers (aka 'flags') to modify the behavior of bash commands
flags will allow you to filter certain things when you are searching or performing functions 

##### Using tab auto-complete for file name and folder name completion
saves time
##### Using the up-and-down-arrows to pull up previous commands
nice 
##### Covered the following bash commands:


Bash Cheatsheet

1. **pwd** - shows the current dir that user is in

2. **cd .** - leave you in same directory

2. **cd ..** - go up a dir

2. **cd -** - last directory 

3. **mkdir** - make a dir

4. **ls** - ~dir 
    1. **ls -S** - lists dir by file size
    1. **ls -a** - shows all dir, *including* hidden files!
    1. **ls -1 > *name.txt*** - make a text file
    1. **ls -Shal** - rounds size of files to KB
    1. **ls *.ext*** - displays all files of that extension (i.e.txt)
    
6. **rm** - remove file (rm + filename)

7. **rm -r** - remove dir (rm -r + dirName)

8. **cd** **~** - "go home"

9. **cat + *name.txt*** - displays file info 

10. **cat file.txt | wc -l** - shows word count of file 

1. **cat file.txt | cut -f 2,2 | sort | uniq -c** - will cut rows of a file (-f) (n,n); sorting according to unique files -c = count of occurences  

1. **cat file.txt | cut -f 2,2 >> newFile.txt**- make a new file containing those cut contents 

10. **mv + *fileName.ext* + *dir name*** - move a file into a different dir

11. **mv + *filename.ext* + *newName.txt*** - rename file

22. **cp + *fileName.ext* + *newName.ext*** - copy file

12. **conda list | grep "keyword"** - returns contents in ls with "keyword"

13. **head *file.txt*** - peek into few lines of file // head/tail

14. **head -n# + *fileName.ext*** - peek into specified # of lines

15. **conda info --envs** - displays environments list

16. **source activate + *env*** - get into env. + name

17. **source deactivte** - get out of env.

18. **conda update conda** - updates base env. 

1. **conda create -n new_env *packages*** - creates a new env w/ certain packages, and/or programs 

19. **tabview + *fileName.ext*** - shows file contents nicely

20. **n + *fileName.ext*** - shows file contents 

21. **nano + *fileName.ext*** - shows file contents ... tabview is nicer ...

23. **echo "message" > *fileName.ext*** - redirect -- replace info with new msg // rewrites any current info

43. **echo "message" >> *fileName.ext*** - append to a file

25. **touch + *fileName.ext*** - create new file 

1. **conda list** - shows all packs

2. **conda info --envs** - lists all environments

3. **conda install 'package'** - install a certain package

1. **| #pipe symbol** - input /output system

1. **grep** - searching for files 

1. **sudo** - allows a user execute a command as another user 

1. **append to the end of a file with ">>"** - adds to a file 

1. **less is more**

1. **weget** - wget + link will download/run script

1. **chmod** - change mode 

1. **ps**

1. **kill PID** - terminates a specific program (PID- program identifier)

1. **find . -type f | wc -1** - find in current directory (.), filter file type (-f), to find # of files

1.  cat AlexAdler.fasta |grep -v '>' | wc -- wc for all 

1. **grep -v ">" AlexAdler.fasta | grep -oE 'A|T|C|G'| sort | uniq -c **-- show number of ACGT

1. cd into documents folder, activate env, then start "jupyter notebook"


