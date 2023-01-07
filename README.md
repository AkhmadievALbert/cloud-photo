# cloud-photo
Ахмадиев Альберт Маратович, 11-904

# P.S.
Запускал на облаках других ребят, так как при создании своего бакета, была ошибка, не хватает лимитов для бакетов.

# Обработка фотографий с лицами людей
## Объекты
### Бакеты
- itis-2022-2023-vvot37-photos
- itis-2022-2023-vvot37-faces
### БД
- vvot37-db-photo-face
### Очереди
- vvot37-tasks
### Триггеры
- vvot37-photo-trigger (сервисный аакаунт **vvot37-face-detection**)
- vvot37-task-trigger (сервисный аккаунт **vvot37-cut-invoker**)
### Функции
- vvot37-face-detection (сервисный аккаунт **vvot37-face-detection**, код из файла **function/crop.py**)
- vvot37-boot (сервисный аккаунт **vvot37-bot-function**, код из файла **function/bot.py**)
### Контейнер
- vvot37-face-cut (сервисный аккаунт **vvot37-cut-invoker**, код из папки **container**)
