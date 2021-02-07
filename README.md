# Devs on a boat
This is intended to be a whitepaper discussing how one could make living in a boat full time and working as a developer a practical possibility.

Please excuse the mess this is in right now! I've very much been in the "throwing my thoughts on a page" step.

Apart from my dissertation I've never written a large document like this, please feel free to make suggestions for how the structure can be improved, especially as this grows.

I'm more than sure there will be things that are actively wrong and I'd be thrilled for these to be pointed out. I've been writing this document for my own use case (classic sailboat with an electric motor, ultimately designed to be able to cross oceans and work indefinitely from a remote destination) but now that this is a communal effort I think it's only proper to broaden this to describe a variety of approaches. More than happy to hear suggesions for how one would do this.

This document is written in Latex (pronounced Lay-tek). Its user experience is kind of ass so I'm open to using a different format but chose Latex as it's a common choice for whitepapers and has lots of nice features around referencing, typesetting, and making indexes - amongst other things. Markdown for example just doens't have this rich set of features although it is much simpler to work with.

# Building

[This medium article](https://medium.com/@rcpassos/writing-latex-documents-in-visual-studio-code-with-latex-workshop-d9af6a6b2815) is pretty handy, I'd recommend it to anyone new to Latex or new to setting up a Latex dev environment.

One can also use overleaf, a web GUI for dealing with Latex documents. I used it until very recently and the instructions for using it are in the article above, towards the end. If you want a no hassle editor, I'd wholeheartedly recommend it (compile times can be slow). This is only free with a premium overleaf trial, though.

## tl;dr

```zsh
# MacOS - installation for VSCode
# this is quite a slow install, not sure if it's a large file or the download mirror is slow
brew install --cask mactex-no-gui 

# You must restart your terminal window for the installation of MacTex CLI tools to take effect.
# Alternatively, Bash and Zsh users can run the command:
eval "$(/usr/libexec/path_helper)"

# mactex has its own package manager - this updates the installed packages
sudo tlmgr update --self
# This is a lot of stuff, and will be quite slow. You might be able to get away without doing this.
sudo tlmgr update --all

# Install the VSCode extension giving on-save-compiling and syntax highlighting, among other things.
# You can also install it through the UI under latex-workshop
ext install latex-workshop
```

At some point I will set up some CI/CD to validate PR's and build a PDF off the master branch and post that somewhere for all to see. Currently one should just render the PDF using your favourite Latex editor.

# Problems
If you're struggling to get the autocompile feature to work you may fix it by running `eval "$(/usr/libexec/path_helper)"` in your VSCode terminal.
