# pw-spi

# pobierz zmiany
git pull

# wypchnij zmiany
git push

# utworz branch
git checkout -b nazwa-brancha
git branch nazwa-brancha
# lista branchy
git branch

# usuwanie brancha
git branch -d nazwa-brancha


# zapis w katalogu systemowym/globalnie
git config --global user.name "Name Name"
git config --globla user.email "example@example.com"

git config --global core.editor emacs


# ustawienie brancha default
git config --global init.defaultBranch main
git config --global init.defaultBranch master


# gdzie jest .gitconfig
git config --list --show-origin


# dodawanie pliku/plikow do staging
git add nazwa-pliku
git add .
git add *.py
git add README.md index.html


git add -h



# status zmian
git status
git status -s


# git diff
git diff --staged
git diff


# add, mod, delete remote url
git remote -v