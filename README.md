# hostingraja.in-Shell-Script-To-Check-Memory-Usage-Disk-Usage-and-CPU-Load-of-Vps-Server-of-HostingRaja


It is very important to know about the RAM,Disk consumption details in Vps server and also about the CPU Load for betterment of your site.

If you want to add more accounts under the server make sure that all these things doesnot exceed the limit.If exceeded server load will become more and will stop all the services.

When a server is under high load, chances are that the number of processes in the "wait" queue are growing each second.
The commands take longer to execute, and soon the server could become non-responsive, leading to a reboot. So, it is important to kill the source of the server load as soon as possible.

So troubleshooting is an good practice to solve the problem By running this script will give you with complete details i.e you will get the calculations how much data usage is done with present account and RAM consumed by it.Also the load exceeds if there is too many hits and you can think about how to optimise the site and also to upgrade the neccessary things.


The given below commands are very usefull to know more about your VPS Server which are commonly used:

=>To check the Ram Availability use this command    free -m

=>To check the disk usage  df -h

=>To check the load w

=>To check os info  cat /etc/*release

=>To check all the running processes within your Linux environment   top -cd32

=>To check the folder size  du -sh /var/

=>To kill the current process kill -9 pid 

ex: kill -9 1234

=>Copy a File from a Remote Server to a Local Server with SSH

ex: rsync -avzhe ssh --progress root@192.168.0.100:/root/install.log /tmp/

=>Copy a File from a Local Server to a Remote Server with SSH

ex: rsync -avzhe ssh --progress backup.tar root@192.168.0.100:/backups/

=>To remove the deferred mail present in mail queue  postsuper -d ALL deferred

=>Back up a single database, you merely create the dump and send the output into a file

mysqldump database_name > database_name.sql


Multiple databases can be backed up at the same time:

mysqldump --databases database_one database_two > two_databases.sql


back up all of the databases on a server:

mysqldump --all-databases > all_databases.sql


=>Restore databases   mysql database_name < database_name.sql
  

Restore a single database from dump of all the databases:

mysql --one-database database_name < all_databases.sql


For more details visit us at hostingraja.in
