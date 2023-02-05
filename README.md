# Python_full_guide

1. Instalacja repozytorium
2. Inicjalizacja gita w repozytorium
mkdir new_repo
cd new_repo
git init
3. Commitowanie zmian
git status
git add <file> lub git add . (dodaj wszytskie dodane lub zmienione pliki)
git commit -m 'jakie zmiany kodu kommitujemy'
git push
4. Tworzenie branchy
git branch <nazwa brancha>
5. Przechodzenie na inny branch
git checkout <nazwa brancha>
6. Dociąganie zmian z brancha do mastera
git status
git add <file>
git commit -m 'jakie zmiany kodu kommitujemy'
Uwaga! nie było git push
git checkout master
git merge <nazwa brancha>
usuwamy brancha
git branch -d test_1
7. Usuwanie plików które nigdy wcześniej nie zostały dodne do repo
git clean
