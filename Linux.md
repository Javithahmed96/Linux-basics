Linux


1. Echo - to print arguments and it shows environmental variable also
      ( ex. by using echo $HOME command we will find home directory )

2. Echo -n  (here -n is an option which is used to print the command without trailing into a new line )

     



Uptime - to show the uptime hours in the command terminal

Internal commands:- (they are more about 30 commands)

Echo, cd, pwd, set , etc,

External commands:- ( pre installed with distribution package manager)

Mv, date, uptime, cp, etc,


To determine the command internal or external use ( type ) command 


Make directories:-

mkdir  command is used to create new directories 

Another way to create directory without parent directory by using ( -p  ) option



Change directory to home directory :- 

Make use of ( cd .. ) command or ( cd )



Relative path and Absolute path :-

/home/user/asia - absolute path

First move to /home/user then cd to asia - relative path

PushD and Popd commands - remember the stack of changing directories



Recursive operation:-

With this command ( -r ) option we can cp , rm files ,it changes or deletes completely the directory


To view the files :-

Using (cat) command

Or to edit the file use the ( > ) symbol followed by ( cat ) command


To create a file under any directories:-

Use the ( touch ) command 



List the files with their read, write permissions:-

ls -l ( here -l is the option which is used to list the files along with their permissions )



To list the hidden files:-

ls -a (here -a is the option used to list the hidden files as ( . . ) )


Command used to search manpages throughout the system:-

apropos 


SHELL :-

echo $SHELL - to identify which shell is on the system

chsh - to change the shell 


Bash shell :- 

Auto completion of commands 

alias ( ex. alias dt=date )

history command

Bash prompt :-
 
To change the bash prompt update PS1 
( Ex. PS1="[\d \t \s \h]" )
It’ll show date, time, shell, and hostname in prompt


Export env :-

export PROJECT=MERCURY

Adding a ( .profile )
echo 'export PROJECT=MERCURY' >> /home/bob/.profile

Above terms PROJECT=MERCURY is an example



