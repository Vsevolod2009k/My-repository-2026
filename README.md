# Инициализируем локальный Git в папке проекта
git init

# Добавляем все файлы в отслеживание
git add .

# Делаем первый коммит (запиши понятное сообщение)
git commit -m "Initial commit: basic IT site structure"

# Подключаем удалённый репозиторий (вставь свой URL вместо примера)
git remote add origin https://github.com/username/my-it-site.git

# Отправляем код на GitHub
# Если основная ветка называется main (чаще всего):
git push -u origin main

# Если вдруг ветка называется master (редко сейчас):
# git push -u origin master
