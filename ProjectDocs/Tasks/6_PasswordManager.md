### ✳️ Task 6. Password Manager

**Назначение:**  
Создание и хранение безопасных паролей.

---

#### Поведение и логика:

1. **“Generate Password”:**
   - Ползунок длины (6–24 символа).
   - Чекбоксы: Letters / Numbers / Symbols.
   - Кнопка “Generate”:
     - генерирует пароль (рандом).
     - рассчитывает strength (по длине и символам).
     - обновляет цвет полоски (красный/жёлтый/зелёный).

2. **“Save Password”:**
   - Сохраняет запись `{service, username, password}` в Keychain/CoreData.

3. **“Saved Passwords”:**
   - Список всех сохранённых записей.
   - Swipe → Delete.
   - Long press → Copy to clipboard.

4. **Без подписки:**
   - Любая попытка → Paywall.

---

#### Acceptance Criteria:
✅ Генерация и визуализация работают.  
✅ Список сохраняется и удаляется.  
✅ Копирование в буфер реализовано.  
✅ Без подписки Paywall.