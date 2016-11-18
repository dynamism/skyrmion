# skyrmion

Why is this here? Utilizing the cli (command line) in your favorite shell is essential for efficient administration of your system | network. I like to BASH (Bourne Again SHell - https://www.gnu.org/software/bash/bash.html). Recently, a friend shared his difficulty with writing scripts to help him automate and update tasks within RHEL https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux. 

If you're new to nix, or just want to improve with your operating system's command line interface. I recommend, getting in there, start looking around and running commands. My experience has been the more you manipulate your system textually through a cli, the more you will learn about systems architecture and efficient work flows. Just as in most things, there is no sbstitute for practice. If a command syntax is easier to copy and paste rather than typing. Type it. In no time you will be rocking out with your mouseout. BASH Reference Manual -RTFM https://tiswww.case.edu/php/chet/bash/bashref.html 

Back to my friend, his main complaint about bash scripting seemed to be the lack of GUI. I responded with the appropiate,"how dare you sir"! GUI elements can easily be incorporated into bash scripts. Such as mouse events and color graphics. Why one would need or want this is a different matter altogether. For my friend N.,I have thrown together skyrmion.sh. A BASH script that walks you through some elements of mouse events by capturing mouseover x,y and click events then passing them to keypress with trapping. For those with an interest, it may be of some use.

I can't take any credit for this bit of bash. Most of the original work was written by Chris F. A. Johnson - if you want to learn more about shells, command line interfaces and their histories, here are a few URLS; 



http://cfajohnson.com/shell/?2009-10-19_Pro_Bash_Programming-Scripting_the_GNU-Lunix_Shell 


http://www.unix.org/what_is_unix/history_timeline.html


http://amturing.acm.org/award_winners/thompson_4588371.cfm 


http://amturing.acm.org/award_winners/ritchie_1506389.cfm


http://cacm.acm.org/opinion/interviews/22550-the-a-z-of-programming-languages-bourne-shell-or-sh/fulltext


Target:

Anyone interested in learning a little BASH

Usage:

wget https://github.com/dynamism/skyrmion/blob/master/skyrmion.sh

d/l into a working dir. wget curl whatev then open the file in your favorite editor and BASH! 

(WARNING - Do Not Run Unsandboxed Scripts You Do Not Understand) 

Finally $chmod +x  or $chmod u+x then $./skyrmion.sh or $bash skyrmion.sh
                        

l8r
