# WordZap — Политика конфиденциальности / Privacy Policy

**Дата вступления в силу: 12 марта 2026 г.**  
**Effective date: March 12, 2026**

---

## 🇷🇺 Русский

Настоящая Политика конфиденциальности описывает, какие данные собирает приложение WordZap («Приложение»), как они используются и какие права есть у пользователя в отношении этих данных.

Используя Приложение, вы соглашаетесь с условиями настоящей Политики. Если вы не согласны — пожалуйста, не используйте Приложение.

---

### 1. Какие данные мы собираем

#### 1.1 Данные учётной записи

При регистрации или входе через электронную почту или Google-аккаунт мы получаем:

- адрес электронной почты;
- имя пользователя (если указано);
- идентификатор аккаунта (UUID), присвоенный Приложением.

#### 1.2 Данные об устройстве

При каждом запуске Приложение отправляет на сервер следующие технические данные:

- анонимный идентификатор устройства (Android ID);
- версию Приложения.

> 💡 Эти данные используются исключительно для подсчёта числа установок и проверки актуальности версии. Они не позволяют идентифицировать конкретного человека.

#### 1.3 Пользовательский контент

Слова, переводы и заметки, которые вы вводите в Приложении, хранятся локально на вашем устройстве. На серверы Приложения эти данные не передаются.

#### 1.4 Данные, передаваемые в GigaChat

Если вы используете функцию AI-подсказок и вводите ключ GigaChat API, Приложение отправляет запросы напрямую на серверы GigaChat (Сбербанк) со следующими данными:

- изучаемое слово — для получения примеров использования и переводов;
- ваш личный ключ API.

> 💡 Ключ GigaChat хранится только на вашем устройстве и никогда не передаётся на серверы WordZap. Обработка данных регулируется политикой конфиденциальности Сбербанка.

#### 1.5 Голосовые данные

При использовании функции голосового ввода звук передаётся в стандартный механизм распознавания речи Android. WordZap не записывает и не хранит голосовые данные.

#### 1.6 Данные статистики

История ваших ответов (правильные / неправильные) хранится локально для отображения графика активности. Эти данные не покидают устройство.

---

### 2. Как мы используем данные

Собранные данные используются только для следующих целей:

- обеспечение входа в учётную запись и синхронизация между устройствами;
- проверка актуальности версии Приложения и уведомление об обновлениях;
- подсчёт числа установок в аналитических целях (анонимно);
- предоставление функции AI-подсказок через сервис GigaChat.

Мы не продаём, не передаём и не раскрываем ваши данные третьим лицам в коммерческих целях.

---

### 3. Разрешения приложения

Приложение запрашивает следующие системные разрешения:

| Разрешение | Для чего используется |
|---|---|
| `INTERNET` | Вход в учётную запись, проверка версии, запросы к GigaChat API |
| `RECORD_AUDIO` | Голосовой ввод слов и заметок. Запрашивается только при нажатии на микрофон. Аудио не сохраняется |
| `POST_NOTIFICATIONS` | Уведомление об успешном экспорте словаря. Запрашивается однократно при первом экспорте |
| `READ_EXTERNAL_STORAGE` | Импорт файлов CSV и Excel на Android 12 и ниже. На Android 13+ не используется |
| `RECEIVE_BOOT_COMPLETED` | Восстановление виджета на рабочем столе после перезагрузки устройства |

---

### 4. Хранение и защита данных

Большинство данных (слова, переводы, заметки, статистика, настройки) хранятся исключительно на вашем устройстве. Они недоступны нам без вашего явного действия (например, экспорта).

Данные учётной записи хранятся на защищённом сервере. Передача данных осуществляется по протоколу HTTPS.

Ключ GigaChat API хранится в защищённом локальном хранилище устройства и не передаётся на серверы WordZap.

---

### 5. Ваши права

Вы имеете право:

- получить информацию о том, какие данные о вас хранятся;
- удалить учётную запись и связанные с ней данные, обратившись к нам на почту support@avzory.com;
- экспортировать все свои слова и переводы в файл CSV через меню **⋮ → Экспорт**;
- в любой момент отозвать разрешение на микрофон или уведомления в настройках Android.

---

### 6. Дети

Приложение не предназначено для детей младше 13 лет. Мы не собираем намеренно персональные данные лиц, не достигших этого возраста. Если вам стало известно, что ребёнок передал нам данные без согласия родителей — пожалуйста, свяжитесь с нами.

---

### 7. Изменения в политике

Мы можем обновлять настоящую Политику. При существенных изменениях Приложение уведомит вас. Актуальная версия всегда доступна в настройках Приложения.

Продолжение использования Приложения после публикации изменений означает ваше согласие с обновлённой Политикой.

---

### 8. Контакты

По вопросам, связанным с настоящей Политикой конфиденциальности, вы можете обратиться к нам:

- через раздел **Меню → Обратная связь** в Приложении;
- по электронной почте, указанной на странице Приложения в Google Play.

---
---

## 🇬🇧 English

This Privacy Policy describes what data the WordZap application ("the App") collects, how it is used, and what rights you have regarding your data.

By using the App, you agree to the terms of this Policy. If you do not agree, please do not use the App.

---

### 1. What Data We Collect

#### 1.1 Account Data

When you register or sign in via email or Google account, we receive:

- email address;
- username (if provided);
- account identifier (UUID) assigned by the App.

#### 1.2 Device Data

Each time the App launches, it sends the following technical data to the server:

- anonymous device identifier (Android ID);
- App version.

> 💡 This data is used solely to count the number of installations and verify that the App is up to date. It cannot be used to identify a specific individual.

#### 1.3 User Content

Words, translations, and notes you enter in the App are stored locally on your device. This data is not transmitted to the App's servers.

#### 1.4 Data Sent to GigaChat

If you use the AI hints feature and enter a GigaChat API key, the App sends requests directly to GigaChat servers (Sberbank) containing:

- the word being studied — to generate usage examples and translations;
- your personal API key.

> 💡 Your GigaChat API key is stored only on your device and is never transmitted to WordZap servers. Data processing by GigaChat is governed by Sberbank's privacy policy.

#### 1.5 Voice Data

When using the voice input feature, audio is passed to the standard Android speech recognition engine. WordZap does not record or store any audio data.

#### 1.6 Statistics Data

Your answer history (correct / incorrect) is stored locally to display your activity chart. This data does not leave your device.

---

### 2. How We Use Data

Collected data is used solely for the following purposes:

- enabling account sign-in and cross-device synchronisation;
- checking the App version and notifying you of updates;
- counting the number of installations for anonymous analytics;
- providing the AI hints feature via GigaChat.

We do not sell, transfer, or disclose your data to third parties for commercial purposes.

---

### 3. App Permissions

The App requests the following system permissions:

| Permission | Purpose |
|---|---|
| `INTERNET` | Account sign-in, App version checks, GigaChat API requests |
| `RECORD_AUDIO` | Voice input of words and notes. Requested only when the microphone button is tapped. No audio is stored |
| `POST_NOTIFICATIONS` | Notifying you when a dictionary export is complete. Requested once, on the first export |
| `READ_EXTERNAL_STORAGE` | Importing CSV and Excel files on Android 12 and below. Not used on Android 13+ |
| `RECEIVE_BOOT_COMPLETED` | Restoring the home screen widget after a device reboot |

---

### 4. Data Storage and Security

Most data (words, translations, notes, statistics, settings) is stored exclusively on your device and is not accessible to us without your explicit action (such as an export).

Account data is stored on a secure server. All data transmission uses the HTTPS protocol.

Your GigaChat API key is stored in the device's secure local storage and is never sent to WordZap servers.

---

### 5. Your Rights

You have the right to:

- request information about what data we hold about you;
- delete your account and associated data by contacting us support@avzory.com;
- export all your words and translations to a CSV file via the **⋮ → Export** menu;
- revoke microphone or notification permissions at any time in Android settings.

---

### 6. Children

The App is not intended for children under the age of 13. We do not knowingly collect personal data from individuals below this age. If you become aware that a child has provided us with data without parental consent, please contact us.

---

### 7. Changes to This Policy

We may update this Policy from time to time. When significant changes are made, the App will notify you. The current version is always available in the App's settings.

Continued use of the App after changes are published constitutes your acceptance of the updated Policy.

---

### 8. Contact Us

For any questions regarding this Privacy Policy, you can reach us:

- via **Menu → Feedback** in the App;
- by email listed on the App's Google Play page.

---

*WordZap · Privacy Policy · March 12, 2026*
