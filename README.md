# DZ Sem3

## Создание веток
**git branch имя ветки-создание новой ветки**

## Слияние веток
**git merge branch name- слияние веток**

## Конфликт при слиянии данных веток

**Конфликты возникают когда комиды претендуют на общее рабочее пространство**

## Работа с удаленным репозиторием

1.1.   **При создании _"форка"_(вилки), в локальном репозитории для привязки к _"форку"_ прописываем команду _git clone ссылка из вкладки код_**
1.2.**затем команда _cd имя репозитория к которому необходимо перейти_**
1.3 **Создаём побочную ветку и работаем в ней**
1.4 **Для синхронизации команда: _git push --set-upstream origin имя веки_**

2.1 **Создав свой репозиторий, что бы его связать с локальным прописываем команды:**
* _git branch -M имя основной ветки_
* _git remote add jridin ссылка из вкладки код_
* _git push -u origin имя основной ветки_

2.2 **Для синхронизации изменений в локальном репозитории с удаленным репозиторием прописывается команда _git pull_**

2.3 **Для синхронизации изменений в удаленном репозитории с локальным команда _git push_ при необходимости прописать имя ветки , если добавили ветку, либо сохранения необходимо внести в определённую ветку**

**_конец текста_**