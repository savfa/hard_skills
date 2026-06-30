# React & Redux Roadmap

## React Deep Dive
- [ ] React Fiber: концепция, этапы рендеринга и коммита.
- [ ] Виртуальный DOM и процесс согласования (Reconciliation).
- [ ] Оптимизация: `memo`, `useCallback`, `useMemo`, профилирование.
- [ ] Кастомные хуки: создание, типизация.
- [ ] Обработка ошибок (Error Boundaries).

## Redux & RTK
- [ ] Архитектура Redux и Redux Toolkit (RTK).
- [ ] Слайсы (`createSlice`) и селекторы (`createSelector`).
- [ ] Асинхронность: `createAsyncThunk`.
- [ ] RTK Query: запросы, мутации, кэширование, инвалидация тегов.
- [ ] Оптимистичные обновления (Optimistic Updates).
- [ ] Типизация Redux (useAppDispatch, useAppSelector).

## Self-Check
1. Почему нельзя напрямую изменять state в Redux?
2. В чем разница между `useMemo` и `useCallback`? Когда они могут принести вред производительности?
3. Что такое "prop drilling" и как его избежать?
4. Как работает процесс Reconcilation в React Fiber?
5. Для чего нужен `createSelector` из Reselect (в составе RTK) и как он помогает избежать лишних ререндеров?
