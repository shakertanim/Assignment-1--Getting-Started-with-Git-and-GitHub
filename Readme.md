### Type the command echo 'hello (with a mismatched single quote), and then get out of trouble


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


#### As seen in Listing 1.2, by default the echo command prints its argument to the screen and then puts the new prompt on a new line. The way it does this is by appending a special character called a newline that literally puts the string on a new line. (The newline character is usually written as \n, pronounced “backslash n”.) Because echo is often used in programs to print out a sequence of strings not separated by newlines, there is a special command-line option to prevent the newline from being inserted.


        Example :

        echo -n "Hello, World!!!" 

        Here -n option will not seperate the string by new line (\n).


#### Using the up arrow, print to the screen the strings “fee”, “fie”, “foe”, and “fum” without retyping echo each time.

        Example :

        % echo fee
        fee 

        press up arrow to get the previous command, press backspace to remove fee and replace with fie

        % echo fie
        fie

        press up arrow to get the previous command, press backspace to remove fie and replace with foe

        % echo foe
        foe

        press up arrow to get the previous command, press backspace to remove foe and replace with fum

        % echo fum
        fum


#### Clear the contents of the current tab.

        To clear the contents in current tab :

        % clear

#### Open a new tab, execute echo 'hello', and then exit.

        % sh-3.2# echo 'hello'
        hello
        sh-3.2# exit    

