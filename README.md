# Toralizer
This project is a tool that will connect you through the tor proxy while using command that use connect(), like curl for example. 


This project is based on a tutorial by drJonasBirch, His yt channel : https://www.youtube.com/@dr-Jonas-Birch <br>
The tutorial link : https://www.youtube.com/watch?v=Pebul1c9JKE


# Requirements
Have gcc installed, have make installed, have a bash script in /usr/bin called toralize and having those lines:

```
#!/bin/bash
export LD_PRELOAD=/the/directory/where/you/compiled
${@}
unset LD_PRELOAD
```
And chmod 755 it so its executable.
