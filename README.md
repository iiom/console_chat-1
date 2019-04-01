﻿# Тестовый проект: Консольный чат
Это скорее не полноценный проект, а реализация возможностей `activerecord` в `ruby` приложении.

### Доступные функции:
 * Все пользователи и сообщения хранятся в базе данных
 * Подключен `activerecord`
 * Регистрация пользователей
 * Хранение паролей в шифрованном виде
 * Возможность написать общее сообщение
 * Возможность написать личное сообщение
 * Просмотр сообщений адресованных пользователю
 * После просмотра пользователем, сообщение больше не отображается ему
 * Все происходит в консоли

### Установка Используемая Ruby версия:
    ruby 2.5.1
    
Создайте свой `gemset`, затем выполните команды
    
    gem install bundler
    bundle
    bundle exec rake db:create
    bundle exec rake db:migrate
    bundle exec rake db:schema:load RAILS_ENV=test

### Использвоание / Запуск
    ruby console_chat.rb
