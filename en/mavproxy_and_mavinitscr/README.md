# Mavproxy and mavinit.scr


Mavproxy is a tool we will use to analyse and control the flight logs
[Here](http://tridge.github.io/MAVProxy/) you can find the download instructions.

Some modules will be, probably, necessary.

```sudo apt-get install python-opencv python-wxgtk```

```sudo apt-get install python-wxgtk2.8```

```sudo apt-get install python-matplotlib```

```sudo apt-get install libwxgtk2.8-dev```

Also, we need to download the  `mavinit.scr` script, that contains some aliases, very useful when doing motors tests.For downloading it , do the following:
```
wget http://tridge.github.io/MAVProxy/files/mavinit.scr
```

It is very recommendable to store it in the directory where you will launch Mavproxy, for not need to add a route.

Lastly, with the `less mavinit.scr` command, you can see the different aliases for the graphs.
