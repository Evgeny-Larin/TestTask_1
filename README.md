## Об этом тестовом задании
Это тестовое задание было выдано моим текущим работодателем при устройстве на работу в 2018 году.  
Цель работодателя - оценить мои способности анализировать данные и делать выводы, обсудить задание на собеседовании.  
Решение представлено в блокноте Jupyter Notebook.  

## Исходные данные
Исходные данные находятся в папке source: файл "ЖД база апрель 2017.xlsx".

## Что необходимо сделать:
1. Определить кто основные грузоотправители в каждом регионе (топ-3), остальных объединить в прочих грузоотправителей.
2. Определить основных потребителей металлолома в каждом регионе. Тут выделить крупные заводы, а все остальное объединить в прочих потребителей.
3. Определить топ-10 основных арендаторов вагонов.  
Здесь, во-первых, нужно выделить вагоны из массива по столбцу «NumberVag» (восемь цифр, например 56353063, это вагоны; одиннадцать цифр, например, GESU1131822, это контейнеры).   
Во-вторых, если в столбце «Арендатор» написано «НЕ УКАЗАННА!!!», значит данные нужно взять из столбца «Собств».  
4. Сделать основные выводы по данному массиву информации, представить их в наглядной форме.
