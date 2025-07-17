###
cd "${CxxProjects:?}"
touch ./.clang-format

###
touch ~/.gitignore_global
git config --global core.excludesFile ~/.gitignore_global
