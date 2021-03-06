# Резюме
`git init` - создание репозитория в текущем каталоге  
`git status` - текущее состояние репозитория  
`git add имя_файла` - добавление файла в репозиторий  
`git add .` - добавление в репозиторий всех файлов текущей дериктории   
`git add "*.расширение"` - добавление в репозиторий файлов с одинаковым расширением  
`git reset имя_файла` - удаление файла из репозитория  
`git commit -m " "` - фиксация изменения  
`git log` - просмотр всех изменений в хронологическом порядке   
`git log --summary` - более подробная информация о каждом коммите    
`git remote add имя_удалённого_репозитория URL_репозитория` - добавление удалённого репозитория  
`git push -u имя_удалённого_репозитория имя_ветви` - помещение локальных изменений в удалённый репозиторий. Далее `git push`  
`git pull имя_удалённого_репозитория имя_ветви` - извлечение удалённого репозитория  
`git stash` - скрыть изменения  
`git stash apply` - показать изменения  
`git diff версия_1 версия_2` - сравнить 2 версии  
`git diff HEAD` - сравнение последнего коммита  
`git diff --staged` - сравнение только что сделанных изменений  
`git reset путь` - удаление ненужного файла из накопителя изменений  
`git checkout имя_ветки` - переключение между ветками  
`git checkout -- имя_файла` - возвращение файла; с помощью "--" git обещает командной строке, что дальше нет опций  
`git branch имя_ветки` - создание новой ветки  
`git branch` - просмотр существующих ветвей  
`git checkout -b имя_ветки` - создание новой ветки и переключение на неё  
`git rm имя_файла` - удаление файла с диска  
`git rm -r имя_папки` - удаление папки с диска со всем её содержимым  
`git merge имя_сливаемой_ветки` - объединение веток  
`git branch -d имя_ветки` - удаление ветки после слияния  
`git branch -D имя_ветки` - удаление ветки без слияния  
