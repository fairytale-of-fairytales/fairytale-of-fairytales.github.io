# CLAUDE.md — ИНСТРУКЦИИ ДЛЯ СОЗДАНИЯ И ДЕПЛОЯ FAIRYTALE-OF-FAIRYTALES

Примечание человека: пока так, позже переработаю получше.

## КОНТЕКСТ ПРОЕКТА
Это ядро «Живой Сказки Сказок» — генеративного нарративного пространства. Проект должен быть воплощением минимализма и простоты. Фокус на тексте и взаимодействии.

GitHub репозиторий: `https://github.com/fairytale-of-fairytales/fairytale-of-fairytales.github.io`
Деплой будет осуществляться на `https://fairytale-of-fairytales.github.io`.

## КОМАНДЫ ДЛЯ РАЗРАБОТКИ И СБОРКИ
```bash
# Установка зависимостей
npm install

# Запуск сервера для разработки с горячей перезагрузкой
npx quasar dev

# Сборка проекта для production (результат в `dist/spa`)
npx quasar build
