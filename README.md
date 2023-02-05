# DZ Sem3
## Работа с удалёнными репозиториями  
---
### **Отправка изменений в удалённый репозиторий**
Отправлять изменения в удалённый репозиторий можно параметром **push** с указанием имени репозитория и ветки.
>git push origin main
### **Получение изменений из удалённого репозитория**
Для загрузки изменений из удалённого репозитория используется параметр **pull**. Он скачивает копию текущей ветки с указанного удалённого репозитория и объединяет её с локальной копией.
>git pull  

Также можно просмотреть подробные сведения о загруженных файлах с помощью флага **--verbose**
>git pull --verbose  

### **Слияние удалённого репозитория с локальным**
Слияние удалённого репозитория с локальным выполняется параметром **merge** с указанием имени удалённого репозитория.
>git merge origin

### **Отправка новой ветки в удалённый репозиторий**

Передать новую ветку в удалённый репозиторий можно параметром push с флагом -u, указав имя репозитория и имя ветки.

>git push -u origin new_branch

### **Cоздание копии (удаленного) репозитория**

>git clone http://user@somehost:port/~user/repository/project.git

