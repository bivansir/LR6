# Лабораторная работа №6 "СИСТЕМА КОНТРОЛЯ ВЕРСИЙ"
### Выполнил: студент группы 4218 Семёнов И.И.
---
## Цель работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

---
## Ход работы:
#### 1. Настройка клиента Git
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/1.PNG)
#### 2. Создание локального репозитория
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/2.PNG)
#### 3. Создание файла на GitHub, подтягивание изменений
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/3.PNG)
#### 4. Просмотр логов ветки master
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/4.PNG)
#### 5. Просмотр логов ветки branch1
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/5.PNG)
#### 6. Слияние ветки master и branch1
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/6.PNG)
#### 7. Удаление ветки branch1
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/7.PNG)
#### 8. Добавление файла, его изменение с коммитами, откат последнего коммита
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/8.PNG)
#### 9. Создание ветки для отчёта
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/9.PNG)
#### 10. Создание папки со скриншотами
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/10.PNG)
#### 11. Выгрузка первой партии скриншотов
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/11.PNG)
#### 12. Редактор .md файлов
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/12.PNG)
#### 13. Отформатированный лог команд
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/13.PNG)
#### 14. Пуш изменений на удалённый репозиторий
![alt text](https://github.com/bivansir/LR6/blob/report/screenshots/14.PNG)

#### 14. Список использованных команд
git config --global user.name - просмотр имени клиента Git
git config --global user.email - просмотр почты Git
git config --list - просмотр параметров клиента Git
git clone <ссылка> - клонирование удалённого репозитория
cd <название> - переход в папку
git pull - подтягивание изменений из удалённого репозитория
git log - просмотр изменений без формата
git checkout <название> - переход в другую ветку
git merge <название> - объединение ветки каталога и названной ветки
git commit -m <комментарий> - коммит
git add <название> - добавление в коммит
git branch -d <название> - удаление ветки
git reset --hard HEAD~ - полное удаление последнего коммита
git checkout -b <название> - создание новой ветки и переход в неё
mkdir <название> - создание папки
git log --pretty=format:<строка> - просмотр логов в виде отформатированных строк
git push - загрузка изменений в удалённый репозиторий
---
## Выводы:
Изучил базовые возможности системы управления версиями, получил опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.