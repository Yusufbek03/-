# 🧮 Кредитный калькулятор

Современный кредитный калькулятор с поддержкой PWA, динамическим SEO и оптимизацией производительности.

## ✨ Особенности

- 💰 **Расчет кредитов** с учетом инфляции
- 📱 **PWA поддержка** - работает офлайн
- 🎯 **SEO оптимизация** с динамическими метатегами
- ⚡ **Высокая производительность** (90+ PageSpeed)
- 📊 **Экспорт в Excel/PDF**
- 🔧 **Админ-панель** для настройки SEO

## 🚀 Быстрый старт

### Локальный запуск
```bash
# Простой HTTP сервер
python3 -m http.server 8000

# Или с помощью Node.js
npx serve .
```

### Docker (с WordPress)
```bash
# Запуск WordPress + MySQL
docker-compose up -d

# WordPress будет доступен на http://localhost:8080
```

## 📁 Структура проекта

```
├── index.html              # Главная страница
├── calculator.js           # Логика калькулятора

├── js/
│   ├── sw.js             # Service Worker
│   ├── config.js         # Конфигурация
│   ├── admin.js          # Админ-панель
│   ├── calculator.js     # Основной калькулятор
│   ├── calculator-manager.js # Менеджер калькуляторов
│   ├── charts-manager.js # Менеджер графиков
│   ├── performance-optimizer.js # Оптимизатор производительности
│   ├── add-calculator-example.js # Примеры калькуляторов
│   └── xlsx.min.js       # Библиотека для работы с Excel
├── manifest.json          # PWA манифест
├── favicon.ico            # Favicon сайта
├── icons/                 # Папка с иконками
│   ├── icon.svg          # Иконка приложения
│   ├── link-icon-large.svg # Иконка ссылки
│   ├── pdf-icon-large.svg  # Иконка PDF
│   └── excel-icon-correct.svg # Иконка Excel
├── docker-compose.yml     # Docker конфигурация
└── .gitignore            # Git исключения
```

## 🎛️ Админ-панель

**Доступ:** Тройной клик по логотипу или `Ctrl+Shift+A`

**Возможности:**
- Редактирование SEO формул
- Экспорт/импорт настроек
- Генерация sitemap
- Тестирование формул

## 🔧 Технологии

- Vanilla JavaScript (ES6+)
- Service Worker для PWA
- CSS Grid/Flexbox
- SheetJS для экспорта Excel

## 📈 Производительность

- **LCP**: < 2.5s
- **FID**: < 100ms  
- **CLS**: < 0.1
- Кэширование через Service Worker
- Критический CSS inline

## 🌐 Развертывание

- **GitHub Pages**: Просто push в main
- **Netlify/Vercel**: Drag & drop файлов
- **Docker**: `docker-compose up -d`

## 📝 Лицензия

MIT License - свободное использование и модификация.

---

**Создано для быстрого и точного расчета кредитов** 💚