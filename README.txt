###
cd "${CxxProjects:?}"
touch ./.clang-format

###
mkdir ~/.gitconfig.d/
touch ~/.gitconfig.d/gitignore_global
git config --global core.excludesFile ~/.gitconfig.d/gitignore_global

###
test -d ./.idea/ && touch ./.idea/cmake.xml
