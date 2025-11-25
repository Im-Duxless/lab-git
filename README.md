# Git Branches Exercise

Краткое описание:
Этот репозиторий содержит выполненные задания по работе с ветками и базовой верстке.
Он создан в соответствии с инструкцией: инициализация репозитория с ветками main/develop,
файлов README.md и CHANGELOG.md, использованием .gitignore, и выполнением заданий 3-9.

Настройка разработки:
1. Инициализируйте локальный репозиторий (если нужно):
   git init -b develop
2. Убедитесь, что имя и почта настроены:
   git config user.name "your name"
   git config user.email "your@email.com"
3. Отключите fast-forward для main и develop (пример):
   git config branch.main.mergeoptions "--no-ff"
   git config branch.develop.mergeoptions "--no-ff"
4. Создайте ветку feature для каждого задания, например:
   git checkout -b feature/task-3 . 
   После выполнения изменить в develop через merge:
   git checkout develop
   git merge --no-ff feature/task-3 -m "Merge feature/task-3 into develop"
5. Теги: v1.0, v2.0 добавляются на merge в main (аннотированные теги).

Содержимое репозитория:
- README.md (этот файл)
- CHANGELOG.md (пустой, заполнять при релизах)
- .gitignore (игнорирует logs/ и build/)
- index.html (страница)
- assets/css/style.css
- assets/js/main.js
- COMMIT_LOG.txt (рекомендуемые сообщения коммитов по заданиям)

Ссылка на дополнительный руководящий документ:
Упоминание инструкций по веткам и оформлению коммитов находится в корне репозитория.
# lab-git
