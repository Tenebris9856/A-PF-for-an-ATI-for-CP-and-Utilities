# Прототип фреймворка адаптивного текстового интерфейса *консольных программ* и *утилит*
<!-- Эмблемы — Разное -->
 ![Фреймворк](<https://img.shields.io/badge/Фреймворк-Изергиль%20Ван%20Дер%20Вельде-black?labelColor=white> "АЯ КуМир") \
 ![Контрибьюторы](<https://img.shields.io/github/contributors/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoColor=white&logoSize=auto&label=Контрибьюторы&labelColor=informational>)
 ![Наблюдатели](<https://img.shields.io/github/watchers/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoSize=auto&label=Наблюдатели>)
 ![Звёзды](<https://img.shields.io/github/stars/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoSize=auto&label=Звёзды>)
 ![Обсуждения](<https://img.shields.io/github/discussions/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoColor=white&logoSize=auto&label=Обсуждения&labelColor=important>)

<!-- Эмблемы — Статистика репозитория -->
 - ![Дата публикации](<https://img.shields.io/github/release-date/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoColor=white&logoSize=auto&label=Дата%20публикации&labelColor=informational>)
 - ![Количество загрузок](<https://img.shields.io/github/downloads/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities/total?logo=github&logoColor=white&logoSize=auto&label=Загрузки&labelColor=informational>)
 - ![Количество файлов формата KUM](<https://img.shields.io/github/directory-file-count/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?type=file&extension=kum&logo=github&logoColor=white&logoSize=auto&label=Количество%20файлов%20формата%20KUM&labelColor=important>)

***Репозиторий проекта** для **долговременного хранения исходного кода***.

![Размер файла исходного кода проекта](<https://img.shields.io/github/size/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities/Библиотека-текстового-интерфейса.kum?branch=main&logo=github&logoColor=white&logoSize=auto&label=Размер%20файла%20исход.%20кода%20проекта&labelColor=important>)
[![Загрузка релиза](<https://img.shields.io/badge/Скачать-KUM-red?labelColor=lime>)](<https://github.com/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities/releases/latest/download/Text-interface-library.kum> "Приступить к загрузке&hellip;")

## Описание *проекта*:
***Исследовательский проект** на **предмет интереса к среде обучения школьников программированию*** — **КуМир**, *а также на **реализацию спецификации разметки строк консольных программ и утилит***.

![Дата создания репо](<https://img.shields.io/github/created-at/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoColor=white&logoSize=auto&label=Дата%20создания%20репо&labelColor=informational>)
![Размер репо](<https://img.shields.io/github/repo-size/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?logo=github&logoColor=white&logoSize=auto&label=Размер%20репо&labelColor=important>)
- - -
# Методология оформления *текстового интерфейса* для *консольных программ* и *утилит*
## Структура *программы*:
- **`Заглавие`** — **наименование *программы***, *кратко описывающее **основную цель** или **задачу***:
    - **`Описание`** (**&laquo;`|}…`&raquo;**) — **полное описание *программы***:
        - **`Основное содержимое`** — **основная часть *программы***:
            - **`Программный вывод`**[^1] (**&laquo;`|>-…`&raquo;**) — **сообщение *программы* о *выполненных инструкциях***;
            - **`Системное сообщение`**[^1] (**&laquo;`|}-…`&raquo;**) — **сообщение *разработчика***, *адресованное **пользователю** от **лица программы***;
            - **`Авторское сообщение`** (**&laquo;`| -…`&raquo;**) — **сообщение *разработчика***, *адресованное **пользователю** от **собственного лица***;
            - **`Ввод от пользователя`** (**&laquo;`|}>-…`&raquo;**) — **ввод от *пользователя***.
- **`Завершение программы`** — **сообщение о *завершении программы***, *а также **авторство** или **право собственности***:
    - **`Сообщение о завершении программы`** (**&laquo;`/…`&raquo;**);
    - **`Авторство или правообладатель`** (**&laquo;`/>…`&raquo;**);
    - **`Сообщение о способе закрытия окна программы`** (**&laquo;`/>-…`&raquo;**).

> [!NOTE]
> **Примечание**: ***все функциональные программные модули** разделяются **разделительной линией*** (***последовательность знака равно*** — ***&laquo;`===`&raquo;***); *если внутри **модуля** предусмотрено **заглавие** и **содержимое***, ***они** разделяются **малой разделительной линией*** (***последовательность знака дефиса*** — ***&laquo;`---`&raquo;***).

> [!IMPORTANT]
> **Примечание**: ***длина текстовой строки** зависит от **длины `разделительной линии`***, ***которая** в **свою очередь** зависит от **длины `заглавия программы`***; ***все переносы слов** строго фиксируются по **длине `разделительной линии`***; *однако*, *если **длина текста** заведомо превышает **длину `разделительной линии`***, ***разделительная линия** должна быть продолжена на **четыре*** (***4***) ***символа последовательностью знака дефиса*** (***&laquo;`---`&raquo;***).

<!-- Сноски -->
 [^1]: **Примечание**: *допускается **интеграция программного вывода** и **системного сообщения***.
- - -
# Документация
—
- - -
# Лицензия MIT
> [!IMPORTANT]
> **Правообладатель**: ***Изергиль Ван Дер Вельде***.

***Вы** можете делиться **этим материалом** в **коммерческих целях** при **условии соблюдения следующих пунктов***:
- *Указание **авторства*** (***Attribution***): ***Вы** должны указать **авторство материала** и предоставить **ссылку на лицензию***.

***Полный текст лицензии** доступен по **адресу***: <https://github.com/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities/blob/main/LICENSE>

> [!NOTE]
> **Составитель *документа***: ***Изергиль Ван Дер Вельде***.
> 
> ![Дата последнего внесения изменений](<https://img.shields.io/github/last-commit/Tenebris9856/A-PF-for-an-ATI-for-CP-and-Utilities?path=Readme.md&display_timestamp=committer&logo=github&logoColor=white&logoSize=auto&label=Дата%20последнего%20внесения%20изменений&labelColor=informational>)
- - -
![Правообладатель](<https://img.shields.io/badge/%C2%A9%20Copyright-Изергиль%20Ван%20Дер%20Вельде-black?labelColor=important> "Правообладатель")
- - -
