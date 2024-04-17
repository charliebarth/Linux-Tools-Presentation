# tldr/tlrc: A change of pace from man 

How often have you tried to use a tool and go "man I have no clue how this tool works!" and then
man it, only to still be confused? That's what tldr aims to fix! 

By shortening the amount of information the user is given, it makes it easier to consume and 
figure out how tools work. Plus, as a computer scientist, how often do we actually learn
from an example we (a) did previously or (b) found on a quick Google search. Again, tldr
fixes that!

# Wait so how does tldr actually do that?

To use the tool, simply enter:

```tldr <tool>```

and this will provide you some short examples and important flags for using said tool. The 
largest general use cases will likely be covered by the tool, especially for some of those
that are used a lot.

Along with this, tldr also will have entries for tools that man doesn't. This is because
all tldr pages are created BY the community and are kept up to date whenever someone 
decides they want to add information to the markdown file.

# How can I add to tldr?

By simply going to their GitHub repo, you can create a pull request for either a tool that doesn't
have an entry or update one with more information! It's a really simple process, and in the 
README for the repository, it breaks down all steps to add to this as well!

# Wait, tldr/tlrc? 
tldr got an rust client, which is tlrc. It does the exact same thing, mapped to tldr as an alias
when installed, just so happens to be written in rust for efficiency.

# How can I install it?

There's many different ways to install the tool, so let's go through some most used ones:
1) Once again for my MacOS users, brew can be used:
```brew install tldr```
2) Can use NPM:
```npm install -g tldr```
3) Or even pip3, pythons package manager:
```pip3 install tldr```

And if you want to use tlrc, just replace tldr with tlrc.
