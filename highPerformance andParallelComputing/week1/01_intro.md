# Linux - Part 1

- Linux is open source available under the GNU license.
- Linux has a kernel that serves as an interface between the computer hardware and the shell.

- Open a terminal window:

- To print the current working dir.

```
pwd
```

- To list the content of dir:

```
ls
```

- To print all the flag we need to use with the commands: for example with `ls`

```
man ls
```

- To list all the files including the invisible ones:

```
ls -laF
```

- To change dir: eg to `test`

```
cd test
```

- To move backward from dir:

```
cd ..
```

- To return to home dir:

```
cd $HOME
```

- OR

```
cd ~
```

# Linux - Part 2

- To make a new dir:

```
mkdir test
```

```
ls -laF
```

- To create a file:

```
touch text.txt
```

- To move or rename a file: eg. from current dir to test dir:

```
mv test.txt text
```

- To rename text file

```
mv text.txt text1.txt
```

```
ls
```

- To copy the exact content of a file to another:

```
cp test1.txt text2.txt
```

- To copy Dir

```
cp -R
```

- To remove file

```
rm text2.txt
```

```
rm -R test
```
