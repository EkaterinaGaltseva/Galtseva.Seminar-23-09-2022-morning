 # Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

# Работа с удаленными репозиториями в Git

- Копирование удаленного репозитория. Для этого необходимо взять с Github адрес репозитория, который мы хотим скопировать и в терминале вставить команду *git clone адрес_репозитория*.

- Добавление своего репозитория в общий доступ. Для этого необходимо сначала создать профиль на Github. Затем необходимо соединить локальный и удаленный репозиторий(git remote). Потом отправляем (push) наш локальный репозиторий в удаленный (Github).

- Получение корректировок из удаленного репозитория. Для того, чтобы внесенные изменения отобразились созданные на Github неообходима команда *git pull адрес_репозитория*

- Отключить удаленны репозиторий от локального. Для этого необходимо вызвать команду *git remote remove название_удаленного_ репозитория*

# Создание веток в Git

Ветки можно создавать двумя способами:

1. git branch name_branch, и далее на эту ветку переходим через checkout 

2. git checkour -b name_branch

# Переход между ветками в Git

Есть два способа перехода между ветками:

1. Команда *git checkout name_branch*

2. Команда *git chekout -b name_branch*(использовать в том случае если необходимо создать и сразу перейти на ветку)

# Слияние веток

Для слияния веток необходима команда *git merge name_branch* (name_branch-это название ветки, которую нужно слить с текущей)

# Удаление веток

Если необходимо удаление веток используем команду *git branch -d name_branch*