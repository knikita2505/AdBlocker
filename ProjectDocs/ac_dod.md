## 1. Финальные Acceptance Criteria

✅ Все экраны связаны навигационно  
✅ Любое действие → Paywall без подписки  
✅ Подписка активирует все функции  
✅ Dashboard отображает актуальный статус  
✅ Face ID работает и сбрасывается после выхода  
✅ SmartGuard выдаёт Trust Score с цветами  
✅ Password Generator генерирует и сохраняет данные  
✅ Все UI-элементы в Clay стиле  
✅ Apphud интегрирован и успешно тестируется в sandbox  
✅ В Dark Mode интерфейс выглядит корректно  
✅ Offline режим доступен, Paywall выключен  
✅ Логирование событий (`screen_view`, `paywall_open`, `purchase_success`)  

---

## 2. Definition of Done (DoD)

- Приложение собирается без ошибок на Xcode 16+.  
- Все функции реализованы и протестированы вручную.  
- UI соответствует Clay Design System.  
- Все сценарии (U1–U7) выполняются end-to-end.  
- Paywall flow проходит покупку и возвращает `isProUser=true`.  
- Face ID, генератор и SmartGuard работают стабильно.  
- Analytics и restore purchase протестированы.  
- Performance: нет лагов, фризов, memory leaks.  
- Проект готов к публикации в App Store.