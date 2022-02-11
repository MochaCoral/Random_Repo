# Labradour Report the Third: The short but sweet one
Hey there, this should be a good short and sweet lab report featuring the super useful action of streamlining your ssh configuration. In this, we'll go right to the .ssh directory (privy to those but the most battlehardened commandline users), which should be in the home directory. There, you will create a config file if there isn't one already. And add the following lines
```
Host ieng6
    Hostname ieng6.ucsd.edu
    User cs15lwi22zzz(username here)
```
substituting the hostname and user as well as name for whatever purpose you so choose, here is mine:

![screnshet](images\ssh-config.jpg)

proudly displayed in its grainy vscode glory

Once you do this, you can remote into whatever remote location you can, watch:
![how fancy](images\scp-streamline.jpg)

Here I use the power of scp to copy `testFile.md` from my local machine to the remote directory, without having to copy the *verbose* username.
