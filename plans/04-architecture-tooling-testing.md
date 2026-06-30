# Architecture, Tooling & Testing

## Architecture

### 1. Feature-Sliced Design (FSD)
*   **Руководство:** Архитектурная методология, разбивающая приложение на слои (app, pages, widgets, features, entities, shared) и сегменты. Цель — предсказуемость и независимость кода.
*   **Поиск:** "Feature-Sliced Design official documentation", "FSD methodology overview".

### 2. Монорепозитории
*   **Руководство:** Подход, при котором несколько проектов/библиотек живут в одном репозитории.
*   **Инструменты:** pnpm workspaces, Turborepo.
*   **Поиск:** "Monorepo vs polyrepo", "Turborepo getting started".

---

## Tooling

### 1. Сборщики (Vite/Webpack)
*   **Руководство:** Инструменты превращения исходного кода в оптимизированные файлы для браузера. Vite использует ES-модули для быстрой разработки.
*   **Поиск:** "Vite vs Webpack comparison", "Настройка vite.config.ts".

### 2. Линтинг и форматирование
*   **Руководство:** ESLint — статический анализ кода, Prettier — форматирование. Husky и lint-staged позволяют запускать их автоматически перед коммитом (git hooks).
*   **Поиск:** "ESLint configuration tutorial", "Husky lint-staged setup".

---

## Testing

### 1. Unit & Integration Testing
*   **Руководство:** Unit — тестирование отдельных функций/компонентов. Integration — тестирование связок.
*   **Инструменты:** Vitest, React Testing Library (RTL).
*   **Поиск:** "React Testing Library best practices", "Vitest vs Jest".

### 2. Интеграция с API (MSW)
*   **Руководство:** Mock Service Worker (MSW) перехватывает запросы на уровне сети. Идеально для тестов, где нужен бэкенд.
*   **Поиск:** "MSW getting started", "Mock API in tests".

### 3. E2E-тестирование
*   **Руководство:** Автоматизация действий пользователя в браузере.
*   **Инструменты:** Playwright.
*   **Поиск:** "Playwright browser automation tutorial".
