# 🚀 Руководство по публикации на GitHub Pages

## ✅ Что уже готово

- ✅ **Git репозиторий инициализирован**
- ✅ **Все файлы добавлены в Git**
- ✅ **Первый коммит создан**
- ✅ **Удаленный репозиторий добавлен**
- ✅ **Проект готов к публикации**

## 🔐 Аутентификация в GitHub

Для пуша в GitHub нужна аутентификация. Выберите один из способов:

### Способ 1: Personal Access Token (Рекомендуется)

1. **Создайте Personal Access Token:**
   - Перейдите в GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
   - Нажмите "Generate new token (classic)"
   - Выберите scope: `repo` (полный доступ к репозиториям)
   - Скопируйте токен

2. **Используйте токен для пуша:**
   ```bash
   git push -u origin main
   # Username: gorbunovdmitry
   # Password: [вставьте ваш Personal Access Token]
   ```

### Способ 2: SSH ключи

1. **Создайте SSH ключ:**
   ```bash
   ssh-keygen -t ed25519 -C "your_email@example.com"
   ```

2. **Добавьте ключ в GitHub:**
   - Скопируйте публичный ключ: `cat ~/.ssh/id_ed25519.pub`
   - GitHub → Settings → SSH and GPG keys → New SSH key

3. **Измените URL репозитория:**
   ```bash
   git remote set-url origin git@github.com:gorbunovdmitry/6250-1.git
   git push -u origin main
   ```

## 🌐 Настройка GitHub Pages

После успешного пуша:

1. **Перейдите в репозиторий:** https://github.com/gorbunovdmitry/6250-1
2. **Настройте GitHub Pages:**
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save

3. **Дождитесь деплоя** (1-2 минуты)

4. **Ваш сайт будет доступен по адресу:**
   ```
   https://gorbunovdmitry.github.io/6250-1/
   ```

## 📱 Структура сайта

- **Главная страница:** https://gorbunovdmitry.github.io/6250-1/
- **Информационная страница:** https://gorbunovdmitry.github.io/6250-1/landing.html
- **Конфигуратор стикеров:** https://gorbunovdmitry.github.io/6250-1/designer-advanced.html

## 🎯 Что включено в проект

- **440 стикеров** с разными дизайнами, цветами, формами и толщинами
- **Интерактивный конфигуратор** с живым предварительным просмотром
- **Мобильная оптимизация** для iOS устройств
- **Карусельная навигация** для выбора параметров
- **Адаптивный дизайн** для всех устройств

## 🔄 Обновление сайта

Для обновления сайта:
```bash
git add .
git commit -m "Описание изменений"
git push origin main
```

GitHub Pages автоматически обновит сайт через 1-2 минуты.

## 📊 Статистика проекта

- **477 файлов** в репозитории
- **440 стикеров** (PNG изображения)
- **3 HTML страницы** (index, landing, designer-advanced)
- **Размер:** ~200MB (в основном изображения)

## 🎉 Готово!

После выполнения всех шагов ваш проект будет доступен в интернете по адресу:
**https://gorbunovdmitry.github.io/6250-1/**
