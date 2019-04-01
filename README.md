﻿# Тестовый проект: Консольный чат
Это врятли можно считать полноценным проектом, скорее реализация возможностей `activerecord` в `ruby` приложении.

### Доступные функции:
 * Все пользователи и сообщения хранятся в базе данных
 * Подключен `activerecord`
 * Регистрация пользователей, условная
 * Общие сообщения
 * Возможность написать общее сообщение
 * Возможность написать личное сообщение
 * Просмотр общих сообщений
 * Просмотр личных сообщений
 * Все происходит в консоли

### Установка Используемая Ruby версия:
    ruby 2.5.1
    
Создайте свой `gemset`, затем выполните команды
    
    gem install bundler
    bundle
    rake db:create
    rake db:migrate
    bundle exec rake db:schema:load RAILS_ENV=test

### Использвоание / Запуск
    ruby console_chat.rb
