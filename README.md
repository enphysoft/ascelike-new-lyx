# ascelike-new-lyx
Lyx template for ASCE journal publications

# How to install and use Lyx template of ASCE-like style

sudo mkdir      /usr/share/texmf/tex/latex/ascelike-new
sudo mkdir      /usr/share/texlive/texmf-dist/bibtex/bst/ascelike-new

sudo cp ascelike-new.cls        /usr/share/texmf/tex/latex/ascelike-new/
sudo cp ascelike-new.bst        /usr/share/texlive/texmf-dist/bibtex/bst/ascelike-new

sudo texhash 
sudo cp         ascelike-new.layout     /usr/share/lyx/layouts/

# Lyx Install
* Open Lyx program and reconfigure. 
