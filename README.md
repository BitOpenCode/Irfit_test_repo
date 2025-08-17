# IRFIT APP V2

Адаптивное фитнес приложение на React + TypeScript + Tailwind CSS

## 🚀 Деплой на GitHub Pages

### Проблема
GitHub Pages показывает белый экран из-за конфликта между старой и новой системой деплоя.

### Решение
1. Перейдите в **Settings → Pages** вашего репозитория
2. Измените **Source** с **"Deploy from a branch"** на **"GitHub Actions"**
3. Убедитесь, что выбран workflow **"Deploy to GitHub Pages"**

### Текущий статус
- ✅ GitHub Actions настроены и работают
- ✅ Приложение собирается локально
- ❌ GitHub Pages использует старую систему деплоя

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