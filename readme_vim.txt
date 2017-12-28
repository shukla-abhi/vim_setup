get vim from here
https://bintray.com/veegee/generic/vim_x64
OR https://tuxproject.de/projects/vim/x64/

install py x64
and ruby x64

install pathogen to maintain plugins
replace ~/.vim with ~\vimfiles

mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

download badwolf colorsceheme
run git clone in bundle dir above
git clone https://github.com/sjl/badwolf.git

Plugins:
EasyMotion - Navigation within a file
Netrw -  Filesystem navigation
ctrlp - file finder
Tagbar
ripgrep-vim

generating tags
https://www.topbug.net/blog/2012/03/17/generate-ctags-files-for-c-slash-c-plus-plus-source-files-and-all-of-their-included-header-files/

how to setup multiple tag files?
how to run netrw without issues?
-------------------done--------------------
