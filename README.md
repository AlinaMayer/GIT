# GIT

## Общие комманды

```git init``` создание нового локального репозитория

![git init1](https://user-images.githubusercontent.com/125362721/220983814-22726480-aee0-4348-a314-f579eef2f5b4.jpg)

```git status``` показ текущего состояния репозитория

![git status](https://user-images.githubusercontent.com/125362721/220984694-ba3a4fa9-82c5-44e8-be80-28b848d7d226.jpg)

```git add file_name``` добавление конкретного файла в индексацию

![git add](https://user-images.githubusercontent.com/125362721/220985002-4311de00-521b-494c-ba7d-144531eae667.jpg)

```git add .``` добавление всех непроиндексированных файлов в индексацию

![git add ](https://user-images.githubusercontent.com/125362721/220985175-ba727e4d-3994-4996-aa43-831076a8e94b.jpg)

```git add -A``` индексация абсолютно всех файлов во всем репозитории не зависимо от того, в какой папке сейчас находимся

![git add -Aa](https://user-images.githubusercontent.com/125362721/220985549-626fcce6-8511-4006-9e93-61018f611a02.jpg)

```git commit -m "comment"``` коммит файла с добавлением комментария

![git commit](https://user-images.githubusercontent.com/125362721/220986024-5842bfbd-34f8-449b-b23e-39b7fac96eed.jpg)

```git config -- list``` показ всех настроек

![git config list](https://user-images.githubusercontent.com/125362721/220986927-c87a9b49-09c3-4909-817c-03fb6bb1e6c6.jpg)

```git config --list --local``` показ локальных настроек

![git config list local](https://user-images.githubusercontent.com/125362721/220987135-55562fa9-7051-4172-bc36-e776d5371cdc.jpg)

```git config user.name "user name"``` создание локального пользователя (имя)

![git config user](https://user-images.githubusercontent.com/125362721/220987703-856717cb-b2c5-4793-963a-b300eb4b1869.jpg)

```git config user.email user_email``` создание локального пользователя (почта)

![git config mail](https://user-images.githubusercontent.com/125362721/220988062-2eec360c-305b-4553-ae1a-b9165614877e.jpg)

```git config --global user.name "user name"``` создание глобального пользователя (имя)

![git config user global](https://user-images.githubusercontent.com/125362721/220990394-66ebfd1c-0b11-4ce8-a21d-26ea6c0dd3f8.jpg)

```git config --global user.email user_email``` создание глобального пользователя (почта)

![git config mail global](https://user-images.githubusercontent.com/125362721/220990683-f7f626ff-450d-452c-b67a-84e9d3a59122.jpg)

```git config --unset user.name``` удаление локального пользователя (имя)

![git config unset user](https://user-images.githubusercontent.com/125362721/220990907-a4914bbb-7a15-4da5-aa22-86811fe7f534.jpg)

```git config --unset user.email``` удаление локального пользователя (почта)

![git config unset mail](https://user-images.githubusercontent.com/125362721/220991143-1be49f4c-0163-45c2-a108-8a212b8384cc.jpg)

```cd path_to_the_folder``` переход в заданную папку

![cd](https://user-images.githubusercontent.com/125362721/220991491-3cce165b-7a0f-4ec6-b01a-ab99caedc35d.jpg)

```git rm -r --cached file_name``` удалить файл из индексации

![Git rm -r](https://user-images.githubusercontent.com/125362721/220991883-3443207b-7a9d-4ad6-80c8-1bb225da2a19.jpg)

```git rm -r file_name``` удаление файла и автоматическое добавление этого изменения в индекс

![Git rm -r](https://user-images.githubusercontent.com/125362721/221205043-018afb41-2e1f-4e56-a609-b7dc9616e4c3.jpg)

```git rm -f file_name``` принудительное удаление файла, несмотря на непроиндексированные правки внутри

![Git rm -f](https://user-images.githubusercontent.com/125362721/221205453-ff87eb86-4e8a-46c9-a8e9-c459d2443a19.jpg)

```git mv file_name new_file_name``` переименование файла

![Git mv](https://user-images.githubusercontent.com/125362721/221205996-00a7a112-4cb9-4f9f-8a44-47e58971b6d9.jpg)

```git log``` показывает все коммиты, которые были выполнены

![git log](https://user-images.githubusercontent.com/125362721/221206322-1aa8a5d7-21ce-4d77-af00-ba1ff114586b.jpg)

```git log -p``` дополнительно показывает правки в коммитах

![git log p](https://user-images.githubusercontent.com/125362721/221206639-896ff6d2-b55f-4c31-92be-4a387a67de27.jpg)

```git log --oneline``` показывает только номера коммитов и комментарии к ним

![git log oneline](https://user-images.githubusercontent.com/125362721/221207112-1caaa47c-b5c4-4f30-b6c3-6e36fa0482b6.jpg)

```git show``` показывает информацию по последнему коммиту

![git show](https://user-images.githubusercontent.com/125362721/221207477-6098143c-a18e-41ec-a2cb-e0ebd316d248.jpg)

```git show first_commit_numbers``` показывает определенный коммит по первым цифрам его номера

![git show commit](https://user-images.githubusercontent.com/125362721/221207740-7e37f3ad-7b1d-498f-9451-a723409051cb.jpg)

```git clone``` загружает удаленный репозиторий

![git clone](https://user-images.githubusercontent.com/125362721/221209524-5b4398d0-475a-4a3a-9fbb-99fcecf8f48e.jpg)


