# JavaScript & TypeScript Roadmap

## JavaScript Core

### 1. Event Loop
*   **Руководство:** JS — однопоточный. Event Loop управляет порядком выполнения: синхронный код -> микрозадачи (Promises) -> макрозадачи (setTimeout, DOM events).
*   **Что изучить:** [MDN Concurrency model](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop).
*   **Поиск:** "Event Loop visualizer Philip Roberts", "JavaScript task queue vs microtask queue".

### 2. Замыкания (Closures)
*   **Руководство:** Функция "запоминает" лексическое окружение, в котором была создана. Используется для энкапсуляции данных.
*   **Что изучить:** Понимание лексического окружения (Lexical Environment).
*   **Поиск:** "JavaScript closures explained", "Лексическое окружение JS".

### 3. Прототипы и наследование
*   **Руководство:** В JS наследование основано на прототипах. Каждый объект имеет ссылку на свой прототип.
*   **Что изучить:** `__proto__`, `prototype`, `Object.create()`.
*   **Поиск:** "JavaScript prototypal inheritance", "Prototype chain explained".

### 4. Управление памятью
*   **Руководство:** JS использует автоматический сборщик мусора (Mark-and-Sweep). Утечки возникают при ссылках на объекты, которые не нужны, но не удаляются.
*   **Поиск:** "Memory management in JavaScript", "JavaScript memory leaks common causes".

### 5. Асинхронное программирование
*   **Руководство:** Promises — объекты, представляющие завершение асинхронной операции. `async/await` — синтаксический сахар.
*   **Поиск:** "JavaScript Promises MDN", "Async await best practices".

---

## TypeScript Advanced

### 1. Generics
*   **Руководство:** Создание переиспользуемых компонентов, которые работают с разными типами, сохраняя типобезопасность.
*   **Поиск:** "TypeScript Generics explained", "Generics in TypeScript interfaces".

### 2. Utility Types
*   **Руководство:** Встроенные типы для трансформации существующих (Partial, Pick, Omit, Record).
*   **Поиск:** "TypeScript Utility Types documentation".

### 3. Conditional Types & Infer
*   **Руководство:** Типы, которые зависят от логических условий (как ternary оператор).
*   **Поиск:** "TypeScript conditional types with infer".
