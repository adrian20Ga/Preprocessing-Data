<h1> Bash </h1>

***

<h2> cd </h2>

the command cd change the directory to another directory. the current working directory may be thought of as the directory you are in
return to backward you need to add "..." for example: 
cd documents
cd homeworks
cd ...
cd documents

***

<h2> ls </h2>

this command will lists the contents of your current working directory Example:.
-ls documents:normal
-ls *: show hidden files
-ls -a:show all
-ls -lh:show the files in list format

***
<h2> rm </rm>

remove a file, rm -R delete all files 
***
<h2> mv </h2>

its function is to move files to other paths
•	mv documents /destination
***
<h2> chmod </h2>
switches to the administrator mode to give permissions
•chmod +x - give permission
•chmod -x - denied permission

***

<h2>greep</h2>
is useful to locate and search for patterns that we select
greep examn.csv
  
***
<h2>locate</h2>
its function is to search in the argument of the command
•locate exam.csv
•locate [[upper]] word: will locate the word given and return to upper
***
<h2>stats</h2>
its funtion is to show the stats of a file
•stat preposessing.csv
***
<h2>head</h2>
output the first line of a file
•	head -n # exam.csv: display first "n" lines of the file

***
<h2>tail</h2>
 output the last lines of a file
  
 •	tail -n  examn.csv: display last "n" lines of the file 
 ***
<h2> /dev/null </h2>
puts the archive to the "permanent" bin recycle
 • exam.csv > /dev/null
 ***
 <h2>sort</h2>
 its funtion is to merge lines or sort text and also binaries files
  •sort file: Sort by alphabetic
  •sort -n: Sort the lines numerically by arithmetic value

