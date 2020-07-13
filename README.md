# OS X nanorc files
Optional files for the OS X distro of nano (v2.0.6 at the time I made these) to make it a functional development tool.

The ancient version of nano that is distributed with OS X currently does not support modern regex things like lookaround, so most available syntax highlighting files fail miserably unless you make your own. 

It looks like v2.0.6 only understands POSIX Basic Reg Ex so I have tried to do what I can with the POSIX BRE ruleset.
 
To use:
- grab the files, 
- put the (language name).nanorc files into a directory of your choice, 
- drop the nanorc file into your home directory (~) and rename it to .nanorc

If you did not use ~/nano/ for the language specific .nanorc files then the main nanorc file will need to be updated with the correct path.

The path for the backup files directory should be changed to suit your preference also.



I will add more files as I work in those languages.  HTML, CSS, and JS will be the next likely candidates.
