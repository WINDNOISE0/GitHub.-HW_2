GitHub. HW_2

создаем новую папку

инициализируем в ней гит

создаем файл и коммиитим его
***

1. На локальном репозитории сделать ветки для:
git branch Postman

git branch Jmeter

git branch CheckLists

git branch Bag_Reports

git branch SQL

git branch Charles

git branch Mobile testing
***

2. Запушить все ветки на внешний репозиторий

git push -u origin main
***

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

git checkout Bag_Reports
# nano bag_report1.txt
```
number ID:1
Title: Link 'create new account' Global Menu isn't open when clicking
Seveity: critical
 Priority: hight
 STR:
   1: Open link
   2:Tap to button 'create new account'
 Expected Result:"Registration's window is opened,
 Actual Result":"nothing happens, link isn't opened
```
***

4. Запушить структуру багрепорта на внешний репозиторий

git add .

git commit "Add File to branch BR"

git push -u origin Bag_Report
***

5. Вмержить ветку Bag Reports в Main

git checkout main

git merge Bag_Reports
***

6. Запушить main на внешний репозиторий.

git push -u origin main
***

7. В ветке CheckLists набросать структуру чек листа.

git checkout CheckLists
# nano checklist1.txt
```
1. Модуль "Навбар"

1.1 Визуализация 
1.1.1. Отображение Логотипа компании
1.1.2. Отображение кнопоки бургер меню
1.1.3. Отображение поискового меню
1.2.4. Отображение надписи "Добро пожаловать"

1.2 Функционал 
1.2.1. Ссылка "Логотип"
1.2.2. Поисковое меню
1.2.3. Бургер меню

2. Модуль "Интересное сегодня"

2.1. Блок "Новости"

2.1.1 Визуализация
2.1.1.1 Отображение Списка новостей
2.1.1.2 Размер шрифта
2.1.1.3 Шрифт текста
2.1.1.4 Три карточки новостей
2.1.1.5 Размер изображений в карточках
2.1.1.6 Отображение кнопки "Подробнее"

2.1.2 Функционал
2.1.2.1 Смена цвета картчки при наведении курсора
2.1.2.2 Кнопка "Подробнее"

2.2 Блок "Последние публикации"

2.2.1 Визуализация 
2.2.1.1 Отображение Списка публикаций
2.2.1.2 Размер шрифта
2.2.1.3 Шрифт текста 
2.2.1.4 Три карточки публикацй
2.2.1.5 Размер изображений в карточках
2.2.1.6 Отображение кнопки "Подробнее"

2.2.2 Функционал
2.2.2.1 Смена цвета картчки при наведении курсора
2.2.2.2 Кнопка "Подробнее"
```
***

8. Запушить структуру на внешний репозиторий

git push -u origin CheckLists
***

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main +
***

10. Синхронизировать Внешнюю и Локальную ветки Main

git pull
***
