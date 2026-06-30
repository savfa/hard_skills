# Browser, Performance & Security

## Browser Internals

### 1. Critical Rendering Path
*   **Руководство:** Путь браузера от получения HTML до отрисовки пикселей: DOM -> CSSOM -> Render Tree -> Layout -> Paint -> Composite.
*   **Что изучить:** Как скрипты и стили блокируют рендеринг.
*   **Поиск:** "Critical Rendering Path MDN", "Browser rendering pipeline".

### 2. Продвинутые DOM API
*   **Руководство:** Современные API для оптимизации: `IntersectionObserver` (ленивая загрузка), `ResizeObserver` (отслеживание изменений размеров элементов).
*   **Поиск:** "MDN IntersectionObserver API", "ResizeObserver vs window resize event".

---

## Web Performance

### 1. Core Web Vitals
*   **Руководство:** Ключевые метрики Google: LCP (Largest Contentful Paint - скорость загрузки), INP (Interaction to Next Paint - отзывчивость), CLS (Cumulative Layout Shift - стабильность).
*   **Поиск:** "Google Core Web Vitals guide".

### 2. Оптимизация ресурсов
*   **Руководство:** Сжатие изображений, использование WebP/AVIF, оптимизация шрифтов (font-display: swap).
*   **Поиск:** "Optimize images for web", "Web performance best practices 2026".

### 3. Code Splitting & Tree Shaking
*   **Руководство:** Разбиение бандла на чанки (динамические импорты) и удаление неиспользуемого кода сборщиком.
*   **Поиск:** "Webpack code splitting", "Vite tree shaking".

---

## Security

### 1. CORS & Same-Origin Policy
*   **Руководство:** Механизм защиты, запрещающий скриптам одного источника читать данные другого без разрешения (CORS headers).
*   **Поиск:** "How CORS works", "Same-origin policy MDN".

### 2. Защита от XSS, CSRF, Clickjacking
*   **Руководство:** XSS (инъекции скриптов), CSRF (подделка межсайтовых запросов). Защита: санитайзинг, CSP, Anti-CSRF токены.
*   **Поиск:** "OWASP Top 10 web security", "Content Security Policy MDN".

## Self-Check
1. Опишите Critical Rendering Path. Какие этапы блокируют рендеринг?
2. В чем разница между `IntersectionObserver` и `scroll` event? Что производительнее?
3. Что такое CLS и как его минимизировать в React-приложении?
4. Как работает Same-Origin Policy и зачем нужен CORS?
5. В чем разница между XSS и CSRF и какие стратегии защиты наиболее эффективны против каждого?
