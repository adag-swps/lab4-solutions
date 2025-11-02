Solutions for exercises 8-13 from lab 4

## Exercise 8
Using the find tool, search for all empty files in the home folders of all the users.

```bash find /home -type f -empty ```

## Exercise 9
Using the find tool, search for all regular files in your home folder and save the result of the command to the file ~/my_files.txt.

```bash find ~ -type f > ~/my_files.txt ```

## Exercise 10
Using find search all the files you own.

```bash find ~ -user $USER ```

## Exercise 11
Using find search for all files in the ~ folder that have been modified in the last day.

```bash find ~ -mtime 0 ```

## Exercise 12
Using find, find all files that have the word 'mozilla' in their name and are located in subdirectories of the /usr directory.

```bash find /usr -type f -iname "*mozilla*" ```

## Exercise 13
Using the find program, find all directories with the name bin that are located in the /usr directory.

```bash find /usr -type d -name "bin" ```
