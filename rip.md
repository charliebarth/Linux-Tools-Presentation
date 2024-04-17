# rip: rm improved!

rip add's some basic improvements to rm, the biggest one beig an "undo" feature. Let's give an 
example.

Let's say you want to remove a file, so you enter:

```rip file.txt```

But then you realize, "oh crap! that wasn't the right file!". That's where the -u flag can 
come in handy! Simply just enter:

```rip -u```

Which will undo your most recent removal! 

But wait...

# How does this "undo" work?

It's your lucky day, because it's fairly simlple how it works! Files that are removed are placed
into your "graveyard". This is a directory in: 

```~/tmp/graveyard-$USER```

You also have some simple options of shifting it around if you don't like that:
1) Create an alias where you provide the location such as ```alias rip='rip --graveyard <path>'```
2) Set up an environment variable, called $GRAVEYARD where you set the directory there!

In general, there's a lot more flexibility, ease of use, and much more to rip. Plus, next time 
your accidentally remove your project due in an hour, you don't have to stress!

# What else?

Other than the undo feature, rip is generally the same tool as rm! It's open-source and written 
in Rust, and the project has been completed since 2021. For it's use case, it was quickly created,
debugged, and considered "safe" to use. As always, use this tool at your own risk, but I have 
enjoyed it a lot and consider a lot safer than rm. 

# I'm sold! How can I install it?

Well there's many different options to installing it! Let's go through some of the most common:

1) For all my MacOS users out there, we can use homebrew (my best friend)
```brew install rm-improved```
2) Download the tar bomb and move into your bin:
```tar xvzf rip-*.tar.gz
   mv rip /usr/local/bin'''
3) Use cargo to install it:
```cargo install rm-improved```
