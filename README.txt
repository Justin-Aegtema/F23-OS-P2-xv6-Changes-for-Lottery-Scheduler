Project changes xv6's round robin scheduler into a lottery scheduler

Portions that I changed can be found w CTRL+F "jtb200002"

After you compile and run xv6, you can showcase the program with these .c files in ./xv6/user

Just type in the command, excluding the ".c":
default_tickets.c  
forktickets.c  
getpinfo.c  
high_sleep.c  
high_tickets.c  
processesinuse.c  
random.c  
setticket.c  
stress_equal.c  
switch_tickets.c