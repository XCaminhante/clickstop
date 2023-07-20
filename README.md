# clickstop
Bash script that uses xprop (because xdotool couldn't retrieve PIDs on my system) to send SIGSTOP and SIGCONT signals to the process tree of an application that was clicked on

## USAGE
	clickstop.sh pause will pause the next application you click
	clickstop.sh resume will resume the next application you click
