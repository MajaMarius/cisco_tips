Jump to the front (CTRL-A) and end (CTRL-E)
Undo any commands just put "no at the end of command"
for example if you set hostname with command " hostname Cisco" to undo this just put again the command with no in the front " no hostname "
To view all interface status use 
    
    show ip interface brief
    

To stop asynchronous messagind use the next command on config line that you use :  

    logging synchronous
   
to avoid domain  lookup

    no ip domain-lookup
    
 Easy way to copy running config to startup config file
 
     wr
 
 
     
