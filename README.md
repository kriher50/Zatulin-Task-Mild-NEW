## Описание проекта
Этот проект представляет собой веб-приложение для управления новостями. Оно позволяет пользователям легко получать актуальные новости из различных источников, очищать базу данных и запускать автоматизированные задачи для обновления информации. Проект реализован с использованием фреймворка Laravel и предоставляет удобный интерфейс для работы с новостями.

## Быстрая установка
Если необходимо быстро установить проект, выполните все шаги одной командой:
```bash
git clone https://github.com/kriher50/Zatulin-Task-Mild-NEW-2.git
cd Zatulin-Task-Mild-NEW-2
composer install
npm install
npm audit fix --force
npm audit fix
npm run build
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan db:seed --class=ArticleSeeder
php artisan serve
#   Z a t u l i n - T a s k - M i l d - N E W  
 