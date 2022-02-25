Шпаргалка по Git'у
====================
_____________
## 1. Шпаргалка по основным командам

* *git add* - добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита. По умолчанию git commit использует лишь этот индекс, так что вы можете использовать git add для сборки слепка вашего следующего коммита.

* *git status* - показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

* *git diff* - используется для вычисления разницы между любыми двумя Git деревьями. Это может быть разница между вашей рабочей директорией и индексом (собственно git diff), разница между индексом и последним коммитом (git diff --staged), или между любыми двумя коммитами (git diff master branchB).

* *git difftool* просто запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff.
*git mv* — это всего лишь удобный способ переместить файл, а затем выполнить git addдля нового файла и git rm для старого.

*git clean* используется для удаления мусора из рабочей директории. Это могут быть результаты сборки проекта или файлы конфликтов слияний.

* *git commit* - берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.

## 2. Шпаргалка по ветвлению и слиянию

* *git checkout* - ~применяется~ используется для переключения веток и выгрузки их содержимого в рабочую директорию.

# Тут будет картинка

![Красотка Керриган](Kerrigan.jpg)

# Тут что-то будет

## Продукты для смого простого супа

Продукты (на 3 порции)
Картофель - 2-3 шт.
Лук репчатый - 1 шт.
Морковь (по желанию) - 1 шт.
Масло растительное - 1-2 ст. ложки
Капуста белокочанная - 300-400 г
Зелень - 1 пучок
Соль - 0,5 ст. ложки
Соус соевый (по желанию) - 1-2 ст. ложки

# И тут что-то будет
# И тут что-то будет. Но ничего хорошего

Теперь начну поочередно все сливать. Сначала image, потом product, потом HZ 

# ДЗ 3

## Шпаргалка по работе с удаленным репозиторием

1. Копирование репозитория по ссылке (git clone): чужой удаленный репозиторий -> свой локальный репозиторий
2. Создание удаленного репозитория
    2.1 Создание аккаунта на github
    2.2 Создание репозитория на github
    2.3 Создание и подключение локального репозитория

git push - загрузить на github
git pull - выгрузить с github