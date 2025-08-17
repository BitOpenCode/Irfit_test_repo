# IRFIT APP V2

Адаптивное фитнес приложение на React + TypeScript + Tailwind CSS

## 🚀 Деплой на GitHub Pages

### ✅ Настройки исправлены
- Source: GitHub Actions
- Workflow: Deploy to GitHub Pages

### 🔄 Автоматический деплой
После изменения настроек GitHub Pages автоматически запустит деплой через GitHub Actions.

### 📍 Получение ссылки
После успешного выполнения workflow, ваш сайт будет доступен по адресу:
`https://bitopencode.github.io/lrfit_test_repo/`

## 📁 Структура проекта

```
src/
├── components/          # React компоненты
├── contexts/           # React контексты
├── screens/            # Экраны приложения
└── main.tsx           # Точка входа

public/
├── index.html         # Заглушка для GitHub Pages
├── test.html          # Тестовая страница
└── 404.html          # SPA fallback

.github/workflows/
└── deploy.yml         # GitHub Actions workflow
```

## 🛠️ Локальная разработка

```bash
# Установка зависимостей
npm install

# Запуск в режиме разработки
npm run dev

# Сборка для продакшена
npm run build

# Предварительный просмотр сборки
npm run preview
```

## 🔧 Технологии

- **React 18** - UI библиотека
- **TypeScript** - типизация
- **Tailwind CSS** - стилизация
- **Vite** - сборщик
- **GitHub Actions** - CI/CD

## 📱 Функции

- 🌙 Переключение темы (светлая/темная)
- 📅 Календарь тренировок
- 👤 Профиль пользователя
- 📋 Расписание занятий
- 🔐 Система аутентификации

## 🚨 Важно

После изменения настроек GitHub Pages подождите 2-5 минут для завершения деплоя. 