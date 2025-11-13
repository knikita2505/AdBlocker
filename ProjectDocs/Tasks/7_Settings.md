### ⚙️ Task 7. Settings

**Назначение:**  
Настройки и доступ к Paywall.

---

#### Поведение и логика:

1. **UI:**
   - Clay-карточка “Unlock Unlimited Access”.
   - Тогглы: Notifications, Face ID, Auto Remove.
   - Ссылки: Terms, Privacy, Restore.

2. **Действия:**
   - “Learn More” → Paywall.
   - Изменения toggles → сохраняются в UserDefaults.
   - “Restore Purchases” → вызывает `Apphud.restore()`.
   - При успехе: `isProUser = true`, UI обновляется.

---

#### Acceptance Criteria:
✅ Все toggles сохраняются локально.  
✅ Restore работает.  
✅ Ссылки открываются корректно.  
✅ Clay-дизайн соблюдён.