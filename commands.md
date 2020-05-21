# Commands

* `pwd` - print working directory

* `cd` - change directory

* `ls` - list the content of the current working directory

	* `ls -l` - long listing, adds more information to the default `ls` output

	* `ls -a` - lists all as well as hidden files or directories.

	* `ls -lh {file}` - show properties of the specified file, in human-readable format.

	* `ls {options} {dir}` - show `ls` in the context of the specified directory

* `mkdir {dir}` - make directory

	* `mkdir -p {dirs}` - make the entire directory hierarchy specified

* `touch {file}` - create a file

* `nano {file}` - create the specified file, if it doesn't exist, and open it in nano

* `cat {file}` - read the contents of a file

* `file {file}` - output the file type of any file supplied to it as a parameter.

* `fc-cache -f -v` - rebuild the font cache.

* Create a file named `file1` and directory `dir1`

	```bash
	touch file1
	mkdir dir 1
	```

