# Стратоплан — «Определи свою компетенцию»

Одностраничный сайт-лендинг для школы менеджмента STRATOPLAN. Сделан как тестовое задание: подаёт информацию о тесте «Матрица интерес-компетентность» максимально просто и понятно.

**Демо:** https://YOUR-USERNAME.github.io/stratoplan/

## Что на странице

1. **Первый экран:** надзаголовок «Стратоплан», заголовок «Определи свою компетенцию», четыре вопроса, призыв пройти тест и кнопка. Рядом схема матрицы «интерес — компетентность».
2. **«Зачем нужен этот тест?»:** короткое описание и четыре карточки: быстрый и понятный, универсальный, инструмент руководителя, анализ.
3. **Финальный блок:** «Определите свою компетентность» и вторая кнопка.
4. **Футер:** © 2026 Школа менеджмента STRATOPLAN.

Обе кнопки без перехода, как указано в задании.

## Решения по дизайну

- Одна колонка и короткие блоки, чтобы страницу можно было прочитать за минуту.
- Схема матрицы в первом экране сразу показывает, о чём тест. Анимация линии проигрывается один раз при загрузке.
- Адаптивная вёрстка: корректно отображается на телефоне, планшете и компьютере.
- Светлая и тёмная тема подстраиваются под настройки устройства.
- Учтены настройки «уменьшить движение» и видимый фокус для клавиатуры.

## Технологии

- Чистые HTML и CSS в одном файле `index.html`, без сборки и зависимостей.
- Шрифты Unbounded и Onest через Google Fonts. Если шрифты не загрузились, используются системные.

## Запуск

Откройте `index.html` в браузере. Для публикации используйте GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.

## Структура

```
.
├── index.html   # весь сайт
└── README.md
```

---

# English summary

A one-page landing site for STRATOPLAN management school, built as a test assignment. It presents the "Interest–Competence Matrix" test in a clear, simple way.

- **Sections:** hero with the four key questions and a matrix diagram, "Why take this test?" with four cards, a final call to action, and a footer.
- **Buttons:** both are intentionally non-navigating, as the assignment requires.
- **Design:** single-column layout, responsive, light and dark themes, reduced-motion and keyboard focus support.
- **Tech:** plain HTML and CSS in a single `index.html`, no build step. Fonts (Unbounded, Onest) load from Google Fonts with system fallbacks.
- **Run:** open `index.html` in a browser, or publish with GitHub Pages (Settings → Pages → `main` / root).
