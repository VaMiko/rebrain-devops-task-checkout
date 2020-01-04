# DevOps Education Project 
## [Source](https://rebrainme.com/devops/ "Source")

**Content**
* [Lessons](#first-five-lessons)
* [Main commands](#main-git-commands)
* [Usage Examples](#usage-examples)

Основы работы с *Git*

![Image of Linus Torvalds](https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/LinuxCon_Europe_Linus_Torvalds_03_%28cropped%29.jpg/431px-LinuxCon_Europe_Linus_Torvalds_03_%28cropped%29.jpg)

_Linus Torvalds:_
>Все эти ~~инновации~~, о которых сейчас трубят на каждом углу — чушь собачья. Кто угодно может заниматься инновациями. “Думать иначе” и всё такое… к чёрту. Это бессмысленно. 99 процентов успеха — это проделанная работа.

## First five lessons

* Базовая работа с Git репозиториями
* Работа с хостингами Git репозиториев
* Создание тегов для коммитов
* Описание репозитория в README.md
* Файл gitignore

## Main git commands

1. git init - initialize repository
2. git status - check changes
3. git add - *add* file in repo
4. git log - check commits *history*
5. git tag - attach tag to commit (create alias for hash)
6. gir remote add - attach remote repository
7. git push - send changes to remote repository


### Usage Examples

Add all new files to repo:

    git add .*

Create tag and attach to commit

    git tag -a v0.1-rc -m 'Release candidate version 0.1'

Attach remote repository *origin* with address *https://gitlab.rebrainme.com/gorshmiko/rebrain-devops-task-checkout* to local repo 

    git remote add origin https://gitlab.rebrainme.com/gorshmiko/rebrain-devops-task-checkout


### Course Progress Table

| Lesson 1 | Lesson 2 | Lesson 3 | Lesson 4 | Lesson 5 |
| ------------- |  -------------  |  -------------  |  -------------  |  -------------  |
| :heavy_check_mark: | :heavy_check_mark: |:heavy_check_mark: |:heavy_check_mark:|:heavy_check_mark:|
