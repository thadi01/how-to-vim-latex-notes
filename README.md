# university + latex 
This repo serves two purposes

1. To hold all my university notes
2. Holds my latex master and preamble templates for both me and others to benefit from

Also as a heads up this is for Linux systems (my commands will be using pacman but using the appropriate command for your distro should yield the same results). I'm not sure how relevant this will be for people on Mac or Windows systems but I imagine some of the stuff is still transferable.

## Replicating my env
### Learning the tools
I use vim + latex for my note taking. Recommend getting comfortable with both vim and latex before trying to take notes using either.
Following links should suffice in providing a sufficient background:

**vim:** https://vimschool.netlify.app/introduction/vimtutor/

**latex:** https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

> There are many other fantastic resources online these are just ones I choose. Also if you have vim already installed typing ```vimtutor``` into your terminal will bring up probably one of the best vim tutorials as well

Recommonded as well is to follow this guide (just setting up .vimrc):
https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/

if you opt not to read the above article just run the following commands:
```
mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged
```
if you don't have or have not created a .vimrc the following:
```
touch ~/.vimrc
```

### Setting things up
The following is for arch and arch based distros since that is what I am using but you can replicate everything simply using commands for your 

install vim 

```
sudo pacman -S vim
```

install vim-plug - vim plugin manager of choice 

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

install latex

```
sudo pacman -S texlive
```

install zathura - pdfviewer of choice

```
sudo pacman -S zathura
sudo paccman -S zathura-pdf-mupdf
```


