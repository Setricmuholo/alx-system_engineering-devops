0x0A. Configuration management

In this project i learnt how to use puppet as a configaration management tool. 

  Tasks
0. 0-create_a_file.pp
Create a file - Using Puppet, create a file in /tmp
	File path is /tmp/school
	File permission is 0744
	File owner is www-data
	File group is www-data
	File contains I love Puppet

1-install_a_package.pp
Using Puppet, install flask from pip3
	Install flask
	Version must be 2.1.0

2-execute_a_command.pp
Using Puppet, create a manifest that kills a process named killmenow
	Must use the exec Puppet resource
	Must use pkill
