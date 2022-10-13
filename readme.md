# Словарь GIT
- Первоначальная настройка Git
  ```
    git config --global user.name "имя пользователя"
    git config --global user.email "эл. почта пользователя"
  ```
- Список удаленных подключений к другим репозиториям.
  ```
    git remote
  ```
- Cоздать новый проект в текущей директории
  ```
  git init 
  ```
-  Cоздать новый проект в указанной директории
  ```
  git init folder-name
  ```
- Клонировать репозиторий в текущую директорию
```
git clone https://github.com:nicothin/web-design.git
```
- Включает URL-адрес каждого подключения.
  ```
    git remote -v
  ```
- Создание нового подключения к удаленному репозиторию.
  ```
    git remote add <name> <url>
  ```
- Удаление подключения к удаленному репозиторию с именем.
  ```
    git remote rm <name>
  ```

- Добавить все измененные файлы в индекс репозитория
  ```
  git add .
  ```
- Отправка изменений
  ```
  git remote add origin main 
  git push -u origin main
  ```
- Показать состояние репозитория
  ```
  git status               
  ```  
- Cравнить рабочую директорию и индекс
  ```
  git diff
  ```      
- Зафиксировать в коммите проиндексированные изменения
  ```
  git commit -m "Name of commit"        
  ```    
- Создание ветки
  ```
    git checkout -b root
  ```
- Слияние
  ```
    git checkout root
    git merge main
  ```

![Sofa](/Winx-Club-Enchantix%20%E2%80%94%20%D0%BA%D0%BE%D0%BF%D0%B8%D1%8F.jpg)

  