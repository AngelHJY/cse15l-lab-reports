## Lab Report 1
1. It is not an error. The working directory is `/home`. The `cd` command didn't produce any output because the command is used to navigate the file system by moving from one directory to another. When no argument is provided, it takes the user to the home directory.

![Image](lab1-1.png) 


2. This is not an error. With an argument, the working directory is `/home/lecture1`. This changes the current directory from `/home` to `/home/lecture1`. 

![Image](lab1-4.png) 

3. This is an error. The working directory is `/home`. The `cd` command does not work with file paths, only directories, so it produces error message.

![Image](lab1-7.png)

4. This is not an error. The working directory is `/home`. With no arguments, it lists the contents of the current directory, which is `lecture1` in this case.   

![Image](lab1-2.png)

5. This is not an error. The working directory is `/home/lecture1`. With the argument being a directory, it lists the contents of the /home/lecture1 directory, which are `Hello.class`, `Hello.java`, `messages` and `README`. 

![Image](lab1-5.png)

6. This is not an error. The working directory is `/home`. With the argument being a file, it simply lists the file `/home/lecture1/messages/zh-HK.txt` if it exists.

![Image](lab1--8.png)

7. This is not an error. The working directory is `/home`. Without arguments, `cat` is usually used to read from standard input.Tthe `cat` command waits for my input and reproduce the same text as I typed in.

![Image](lab1-3.png)

8. This is an error. The working directory is `/home/lecture`. With an argument being a directory, it typically returns an error saying it is a directory because `cat` is used for files, not directories.

![Image](lab1-6.png)


9. This is not an error. The working directory is `/home/lecture1`. With an argument being a file, the command `cat` displays the contents of the file. 

![Image](lab1-9.png)


