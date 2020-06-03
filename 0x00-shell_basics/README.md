#!/bin/bash
Shell information
pwd: prints the path of the current working directory  
ls: display the contents list of your current directory
cd: changes the working directory to the user’s home directory
ls -l: display current directory contents in long format
ls -al: display current directory contents, including hidden files using the long format
dir -aln: display current directory contents in long format including hidden files
mkdir: create a directory in a directory
mv: move a file from a directory to another
rm: delete a file
rm -r: delete a directory
cd -: change the working directory to the previous one
ls -la . ..: list all files including hidden in the current, parent and boot directory in long format 
file: print the type of the file
ln -s: create a symbolic link
cp -u * .html: copy all the HTML files from the current working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the current directory
mv [[:upper:]]:move all files beginning with an uppercase letter to the directory
rm * ~: delete all files in the current working directory that end with the character ~
mkdir -p: create different directories in the current directory

