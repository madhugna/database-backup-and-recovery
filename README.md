# database-backup-and-recovery

COMPANY: CODETECH IT SOLUTIONS

NAME: MADHUGNA KADEM

INTERN ID: CT04DN607

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

This task is about learning how to back up a database and restore it in case something goes wrong, like a system crash or data loss. Backing up a database means saving a copy of all the data and its structure so that you can bring it back later if needed. Recovery is the process of using that backup to restore everything to how it was before the problem happened.

In this task, we are working with a MySQL database. The main goal is to create a backup using a tool called mysqldump and then use that backup to restore the database using the mysql command. These are simple command-line tools that come with MySQL and are commonly used for backup and recovery.

The backup process starts by opening the Command Prompt and going to the folder where MySQL is installed, usually inside "Program Files" on your computer. Then, using the mysqldump command, we create a .sql file that contains all the database information. This file can be saved anywhere on your computer. It is a plain text file that includes the commands needed to recreate the database, its tables, and the data inside them.

Once the backup file is ready, the recovery process can be done at any time. To do that, we open the Command Prompt again and run the mysql command to import the .sql file back into MySQL. This will recreate all the tables and restore the data as it was at the time of backup. Before restoring, you need to make sure that the database you're restoring into already exists.

After restoration, we can log into MySQL and check if the tables and data are restored properly. We do this by running SQL commands like USE database_name, SHOW TABLES, and SELECT * FROM table_name. If everything works correctly, it means the backup and recovery process was successful.

This task helps you understand how important it is to take regular backups. If you ever lose data because of a system failure or by mistake, you can use these backups to recover everything quickly. It also teaches you how to use basic SQL tools in real-world scenarios.

The deliverables for this task include the backup script, recovery script, and a Word report that explains each step clearly. The Word report also has space to paste the output of SQL queries after restoring the database. This helps show proof that the backup and recovery were completed successfully.

To complete this task, you only need basic knowledge of MySQL and how to use the command line. All the steps are easy to follow and require just a few commands. This task gives hands-on experience in maintaining and protecting databases, which is an important skill in any IT job.

In summary, Task 4 teaches you how to safely back up your database and restore it when needed. It ensures that your data is never permanently lost and can always be recovered when something unexpected happens. This is one of the most important tasks in database management and is a must-know for anyone working with data.
