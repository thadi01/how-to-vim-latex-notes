# university + latex 
This repo servers two purposes

1. To hold all my university notes
2. Holds my latex master and preamble templates for both my and others to benifit from

Also as a heads up this is for linux systems (my commands will be using pacman since im on arch but using the appropiate command for your distro should yield the same results). I'm not sure how relevant this will be for people on Mac or Windows systems but I imagine some of the stuff is still transferable.

## Replicating my env
### Learning the tools
I use vim + latex for my note taking. Recommend getting comfortable with both vim and latex before trying to take notes using either.
Following links should suffice in providing a sufficient background:

**vim:** https://vimschool.netlify.app/introduction/vimtutor/

**latex:** https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes

> There many other fantastics resources online these are just ones I choose. Also if you have vim already installed typing ```vimtutor``` into your terminal will bring up probably one of the best vim tutorials as well

### Setting things up
The following is for arch and arch based distros since that is what i am using but you can replicate everything simply using commands for your 

install vim 

```
sudo pacman -S vim
```

install latex

```
sudo pacman -S texlive
```

install zathura - this will be our pdf view of choice

```
sudo pacman -S zathura
sudo paccman -S zathura-pdf-mupdf
```


