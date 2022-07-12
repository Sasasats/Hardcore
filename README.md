# Hardcore

1. Сделайте push вашего репозитория и убедитесь, что все коммиты есть на github.
1.1. git push

2. Сделайте новый репозиторий на github.

3. Смените remote в локальном репозитории так, чтобы fetch и push шел на новый репозиторий который был создан в предыдущем шаге.
3.1. git remote remove origin
3.2. git remote add origin git@github.com:Sasasats/Hardcore.git

4. Сделайте push и убедитесь, что второй репозиторий на гитхабе выглядит так же, как и первый.
4.1. git push --set-upstream origin main
4.2. git push --set-upstream origin storm

5. Верните настройки remote в исходное состояние: пул и пуш первого локального репозитория ведет в один удаленный репозиторий на гитхабе.
5.1. git remote remove origin
5.2. git remote add origin git@github.com:Sasasats/Hurt-Me-Plenty.git
