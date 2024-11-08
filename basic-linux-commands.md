Linux Commands

--File Commands
	ls ===>> Directory listing
	ls -al ===>> Formatted listing with hidden files
	ls -lt ===>> Sorting the formatted listing by time modification
	cd dir ===>> Change directory to dir
	cd ===>> Change to home directory
	pwd ===>> show current working directory
	mkdir ===>> dir Creating a directory dir
	cat > file ===>> Places the standard input into the file
	more file ===>> Output the contents of the file
	head file ===>> Output the first 10 lines of the file
	tail file ===>> Output the last 10 lines of the file
	tail -f file ===>> Output the contents of file as it grows,starting with the last 10 lines
	touch file ===>> Create or update file
	rm file ===>> Deleting the file
	rm -r dir ===>> Deleting the directory
	rm -f file ===>> Force to remove the file
	rm -rf dir ===>> Force to remove the directory dir
	cp file1 file2 ===>> Copy the contents of file1 ro file2
	cp -r dir1 dir2 ===>> Copy dir1 to dir2;create dir2 if not present 
	
	------------------------------------------------------------------------

--Process managment
	ps ===>> To display the currently working processes
	top ===>> Display all running process
	kill pid ===>> Kill the process with given pid
	killall proc ===>> Kill all the process named proc
	pkill pattern ===>> Will kill all processes jobs,resume a stopped job in the background
	fg ===>> Bring the most recent job to foreground
	fg n ===>> Bring job n to the foreground
	
	------------------------------------------------------------------------
	
--System info
	date ===>> Show the current date and time
	cal ===>> Show this month's calender
	uptime ===>> Show current uptime
	w ===>> Display who is on line
	whoami ===>> Who you are logged in as
	finger user ===>> Display information about user
	uname -a ===>>  Show kernel infomation
	cat /proc/cpuinfo ===>> Cpu information
	man command ===>> Show the manual for command
	df ===>> Show the disk usage
	du ===>> Show directory space usage
	free ===>> Show memory and swap usage
	whereis app ===>> Show possible location of app
	which app ===>> Show which application will be run by default
	
	---------------------------------------------------------------------------
	
--Searching
	grep pattern file ===>> Search for pattern in file
	grep -r pattern dir ===>> Search recursively for pattern in dir
	command | grep pattern ===>> Search pattern in the output of a command
	licate  file ===>> Find all instances of file
	find . -name ===>> filename Search in the current directory(represented by a period) and below it, for files and directories with names starting with filename
	grep pattern ===>> Searches for all the named processes, that matches with the pattern and, by default, returns their ID
	
	----------------------------------------------------------------------------
	
--File Permission
	chmod octal file ===>> change the permission of file to octal, which can be found separately for user, group, world by adding, 4-read(r), 2-write(w), 1-execute(x)
	
	----------------------------------------------------------------------------
	
--Compression
	tar cf file.tar file ===>> Create tar named file.tar containing file
	tar xf file.tar ===>> Extract the file from file.tar
	tar czf file.tr.gz files ===>> Create a tar with Gzip compression
	tar xzf file.tar.gz ===>> Extract a tar using Gzip
	tar cjf file.tar.bz2 ===>> Create tar with Bzip2 compression
	tar xjf file.tar.bz2 ===>> Extract a tar using Bzip2
	gzip file ===>> Compresses file and renames it to file.gz
	gzip -d file.gz ===>> Decompresses file.gz back to file
	
	----------------------------------------------------------------------------
	
--Network
	ping host ===>> Ping host and output results
	whois domain ===>> Get whois information for domains
	dig domain ===>> Get DNS information for domain
	dig -x host ===>> Reverse lookup host
	wget file ===>> Download file
	wget -c file ===>> Continue a stopped download
	
	----------------------------------------------------------------------------
	
--Shortcuts
	ctrl+c ===>> Halts the current command
	ctrl+z ===>> Stop the current command, resume with fg in the foreground or bg in the background
	ctrl+d ===>> Logout the current session, similar to exit
	ctrl+w ===>> Erase one word in the current line
	ctrl+u ===>> Erase the whole line
	ctrl+r ===>> Type to bring up a recent command
	!! ===>> Repeats the last command
	exit ===>> Logout the current session
	
	
	
	
	
	
	
	
	
	
	
	
	
