# Bash Commands

|Command|Name|Action|
|:---|:---|:---|
|**DIRECTORIES**|
|`pwd`|print working directory|Display path of the current working directory|
|`ls`|list|List of the files you have in the current directory|
|`ls -la`|list long format all|List  directory contents including hidden files with their extensions|
|`ls -laF`|list long formar all File|List  directory contents including hidden files|
|`ls -a`|list all|--|
|`mkdir <directory>`|make directory|create a new directory named "directory"|
|`cd`|chxcange directory|Navigate to parent directory|
|`cd ..`|--|Go to parent directory|
|`rename "..." "..."`|rename|rename the name of the directory to other name|
|`cp -u *.html dir` | |Copy all the files with the same extension and move them to a dirctory|
|`touch {file-name}`|||
|`cp {item}{dir}`|Copy||
|`mv {item}{dir}`|Move||
|`mv {item}{path}`|Rename||
|**OUTUPUT**|
|`rm -r {name directory}`|Remove|--|
|`nc towel.blinkenlights.nl 23`|--|Display Starwars Movie|
|**OTHERS**|
|`date`|date|Display the actual date|
|`cal`|calendar|Display the current MM-YYYY calendar|
|`man`| Manual| Open the Manual, Q= Quit, J= Up, K= Down|
|`code -r {repository}` |Code Repository |Open the folder mode of the repository|
|`grep "#" {file name}` | |Filter the desire text "#" |
|`less {name of the file}` | |Enter the read mode to move with J,K up and down. |
|`head` | | |
|`grep "#" {file} "|" grep "F/t"` | | |
|`head -n {number} "|"tail -n 1` | |See the last desire line|
|`cat`|concatenate|Read and print the information inside a file|
|`echo` | | |
|`cat -b vehicles | grep " 40\t"`| |grab the line|
|**Character classes**|
|`*`|wildcard or globbing|Used as an ALL and its expanded into multiplre files or none id there is no match|
|`?`|any single character| |
|`[abxy]`| | |
|`[[:upper:]]*`| | |
|`[![:digit:]]*`| |Everything does not star with a digit |
|`*[[:lower:]123]`| | |
|ping google.com (to stop: ctr+c)|--|
  - `-h`: highlight
  - `-j`: no high light
  - `-A`: after
  - `-B`: before
 
 ## Exercises
  1. cal -y
  2. ncal (calendar inverted)
  3. ncal -e 1803: 10/April/1803
  4. cal dec 1995: look 21, monday
  5. cal -j
  6. cal -A 3 -B 2
  echo
 
 ## Exercise
1.  `*config*`
2. `*[![:digit:]].*`
3. `?[abc]*`
4. `???*`
