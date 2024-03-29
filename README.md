Установить зависимости
composer install

Скопируйте .env файл
cp .env.example .env

Сгенерировать ключ приложения
php artisan key:generate

Запустите сервер
php artisan serve

Чтобы изменить язык, установите APP_LOCALE в файле .env на ru,eng или ru2. По умолчанию это английский