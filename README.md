
# Yourdanov@IBM	

This is a repository created by Atanas Yourdanov.

It contains different IBM usable, public codes and commands for AIX, VIOS, Linux and IBM i operating systems.

## 1. Large files search

Search a text string within large text file with showing the lines before and lines after the match:

* awk 'c-->0;$0~s{if(b)for(c=b+1;c>1;c--)print r[(NR-c+1)%b];print;c=a}b{r[NR%b]=$0}' b=X a=Y s="search text" filename

- Search in large text file, where:

b=X -> X = lines before the match string;
a=Y -> Y = lines after the match string;
s="text" -> search string

The command is tested only on IBM AIX OS version 6.1 and above.

# For any questions and discussions, please use the IBM TechXchange Power I/O User Group:

# https://ibm.biz/BdmbEG
