# zoxide: I'm never using cd again! 

zoxide in short, allows you to hop directories. We'll show an example later on so just trust
me for right now pls.

# So how does it work?

zoxide remembers the directories you have most recently visited, and places weights on 
each in order to choose what directories you jump to. It gains its inspiration from 
z and autojump, two tools that do similar things but not as well. The weights for these
are determines by the last time visited, along with the most frequently visited, in order 
to ensure the correct directory is chosen when you decide to jump.

Essentially, since computer scientists are lazy, we can save a lot of keystrokes by 
just using z instead of cd to move one directory at a time!

# I still don't get it...

I'd suggest hopping into a terminal and checking it out, or even watching a demo of it 
to try and understand how it works! 

# How can I install?

Once again, there are many different ways to install zoxide so we'll cover some quick ones:
1) Homebrew as always provides an option:
```brew install zoxide```
2) For windows users, you can use the winget command:
```winget install ajeetdsouza.zoxide```
3) Can also use cargo since it's rust based:
```cargo install zoxide --locked```
