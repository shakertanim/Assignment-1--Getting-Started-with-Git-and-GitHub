### Write a command that prints out the string “hello, world”.


echo 'hello


Output : 

bash-3.2$ echo 'hello
> '                        # Completed the string with end single quotation sign
hello

bash-3.2$ echo 'hello
>                          # Ctrl + C
bash-3.2$ 






##### According to the man page, what are the official short and long descriptions of echo on your system?

       echo [SHORT-OPTION]... [STRING]...
       echo LONG-OPTION

        Example :

        Short Option - 

        [root@ip-192-192-11-150 centos]# echo -n "Hello"
        Hello[root@ip-192-192-11-150 centos]# 

        Long Option -

        echo --help
        echo --version 

        These are the long option, but this might not work, because echo itself only prints string whichever it gets.



