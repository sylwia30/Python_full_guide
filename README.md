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
7. (To mi nie dziła :/ ) Usuwanie plików które nigdy wcześniej nie zostały dodne do repo (tego działania nie da się cofnąć)
git clean -n/-nd/-idf
-n usuwa plik/-nd usuwa plik z folderem/-idf interkatywne włączenie usuwania plików i folderów
8. Usuwanie pliku które znajduje się w repo (można cofnąć to działanie)
9. Co zrobić aby cofnąć ruch git add <file>
- po wykonaniu git add <file> mamy pliki gotowe do commitowania ze statusem 'Changes to be committed <nazwy plików>'
- git reset
po wykonaniu tego ruchu pliki nieistniejące w repo mają status 'Untracked files' a będące w repo 'Changes not staged for commit'
9. Cofnięcie wykonanych zmian w kodzie który nie został zakommitowany
git restore <file>
