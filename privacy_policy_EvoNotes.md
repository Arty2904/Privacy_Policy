# Privacy Policy

**Application:** EvoNotes
**Package:** `com.avzory.EvoNotes`
**Effective date:** 2026-11-12
**Contact:** evonotes@avzory.com

---

## 1. Overview

EvoNotes is a personal organizer that lets you create notes, to-do lists, and events on your device. We respect your privacy and collect only the minimum data required to make the app work, sign you in, and sync your content between your devices.

This document explains **what** data we collect, **why** we collect it, **where** it is stored, and **what rights** you have.

## 2. Data We Collect

### 2.1 Account data (when you register or sign in)
| Data | Source | Purpose |
|---|---|---|
| Email address | You (registration / Google Sign-In) | Account identifier, login, account recovery |
| Password (hashed) | You (email registration) | Authentication. We never store the plain-text password. |
| Display name | You / Google profile | Showing your name in the app interface |
| Google account ID token | Google Sign-In | One-time exchange to verify your Google identity, then discarded |
| Authentication token (session) | Our server | Keeping you signed in between launches |

### 2.2 User-generated content (synced to our server when you are signed in)
| Data | Purpose |
|---|---|
| Notes (title, body, category, color, timestamps) | Storing and syncing your notes between your devices |
| To-do groups and items (text, status, due date, reminders, repeat rules) | Storing and syncing your tasks |
| Events (title, body, category, reminder date, repeat rules, subtasks) | Storing and syncing your events |
| Folders / categories and their order, color, visibility | Preserving your organization between devices |
| Audio recordings embedded in notes/events | Storing and syncing voice memos |

### 2.3 Technical data
| Data | Purpose |
|---|---|
| App version, package name (`evonotes`) | Version check, deciding whether to suggest or force an update |
| "Ping" on app start: anonymous device identifier (Android ID — unique to the device and this app, not an advertising identifier), device model (manufacturer and model, e.g. "Google Pixel 9 Pro"), app version, time of launch | Counting installations and active devices (a reinstall on the same phone is not counted as a new device), basic availability monitoring, checking which devices the app runs on |
| "Ping" when the web version (evonotes.avzory.tech) is opened while signed in: your account, browser name (e.g. "Chrome", "Firefox"), app version, time of opening. The Android ID and device model are not collected on the website | Counting web users (the first sign-in on the website counts as an installation, later ones as visits), checking which browsers the website runs in |
| OS-level notification permission state | Showing local reminders for events and to-dos |

We do **not** collect: precise location, contacts, advertising identifiers, browsing history, microphone audio outside of recordings you explicitly create, or analytics about how you tap inside the app.

### 2.4 Data stored only on your device (never sent to us)
- App settings (theme, font, language, view mode, sort order, reminder offset, sidebar state) — stored in `SharedPreferences`.
- A local copy of all your notes, to-dos, and events — stored in a local SQLite database (`sqflite`).
- Soft-deleted items in the trash, until you restore or permanently delete them.
- Scheduled local notifications.
- Events from your phone's calendars (Google Calendar, Samsung Calendar, Outlook and others synced to the device) — only if you turn on calendars in the calendar tab menu. They are read with the Android "Calendar" permission solely to display them in EvoNotes; they are never copied into the app, synced, backed up or sent to our server. The list of calendars you selected is stored on the device.

### 2.5 Sync via Google Drive or Yandex Disk (if you choose it)

Instead of our server, you can sync through your own Google Drive or Yandex Disk. Then:

- what is written to your Drive: notes, to-dos, events, habits, time tracking sessions, folders, some settings (kanban columns, features, pomodoro) and audio recordings, plus copies of this data for the last 7 days — for restoring;
- where: in Google Drive — the "EvoNotes" folder; the app can see only the files it has created itself (the `drive.file` permission), your other files are not accessible to it; in Yandex Disk — the "Applications/EvoNotes" folder;
- connecting a Drive also signs you in to EvoNotes with the same account: our server receives the email (and, for Google, the name) as described in section 2.1, but your content goes directly between your device and the Drive over HTTPS and is not sent to our server;
- data from your Drive is used only for syncing: it is not used for advertising, not sold and not shared with third parties. The app's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements;
- how to stop: sign out of the Drive in the app's sync settings; you can revoke the app's access at any time at [myaccount.google.com/connections](https://myaccount.google.com/connections) or in your Yandex account settings. The files in your Drive remain yours — you can delete them manually.

## 3. Why We Collect This Data (Legal Basis)

- **Performance of a contract** — we need your account data and content to actually provide the service you signed up for.
- **Legitimate interest** — version checks and anonymous pings help us keep the service stable and notify you about important updates.
- **Consent** — microphone access (for audio notes), notification permission and calendar access (to show your phone's calendars) are requested explicitly and can be revoked at any time in your device settings.

## 4. Where Your Data Is Stored

- **On your device**: in the app's private storage (SQLite + SharedPreferences). Other apps cannot read it.
- **On our server** (`avzory.tech`, EU/Russia region): account record and a synced copy of your content, kept while your account exists.
- **In your Google Drive or Yandex Disk**: if you choose disk sync (section 2.5) — your content and its copies for the last 7 days, kept until you delete them.
- **Google / Firebase**: if you use Google Sign-In, Google authenticates you according to its own privacy policy (https://policies.google.com/privacy). We receive only your email, name, and a one-time ID token.
- **GitHub** (`Arty2904/Config`): we host *only* the public update configuration there (minimum version, update links, server URL). No user data is sent to GitHub.

## 5. Sharing With Third Parties

We do not sell your data and we do not share it with advertisers.

We use the following processors strictly to operate the service:
- **Google Firebase Auth / Google Sign-In** — authentication only.
- **Our hosting provider** — to run the sync server.

We will disclose data only when required by applicable law (e.g., a valid legal request).

## 6. Data Retention

- Account and synced content: kept until you delete your account or ask us to delete the data.
- Local data on your device: kept until you uninstall the app or clear its data.
- Trash items: kept locally until you empty the trash.
- Server-side logs (request metadata): kept for a short period for diagnostics, then rotated.

## 7. Your Rights

You can at any time:
- **Access** your data — directly in the app.
- **Edit / delete** any note, to-do, or event individually.
- **Sign out** — removes your session token from the device. Your local copy remains until you choose to clear it.
- **Delete your account** — write to evonotes@avzory.com; we will remove your account and synced content from our server.
- **Revoke permissions** — microphone, notifications and calendar access can be revoked in your device's system settings.

Depending on your jurisdiction (e.g., GDPR), you also have the right to lodge a complaint with your local data protection authority.

## 8. Security

- Passwords are stored only as salted hashes on the server.
- Communication with our server uses HTTPS.
- Your authentication token is stored in the app's private storage, isolated from other apps.
- Local content is stored in the app's sandbox provided by Android.

No system is 100% secure; you are responsible for protecting access to your device.

## 9. Children

EvoNotes is not directed to children under 13. We do not knowingly collect data from children. If you believe a child has provided us data, contact us and we will delete it.

## 10. Changes to This Policy

We may update this policy from time to time. The "Effective date" at the top will reflect the latest version. Significant changes will be announced inside the app.

## 11. Contact

Questions, requests, or complaints: **evonotes@avzory.com**

---
---

# Политика конфиденциальности

**Приложение:** EvoNotes
**Идентификатор пакета:** `com.avzory.EvoNotes`
**Дата вступления в силу:** 2026-11-12
**Контакт:** evonotes@avzory.com

---

## 1. Общее

EvoNotes — это персональный органайзер для заметок, задач и событий. Мы уважаем вашу конфиденциальность и собираем только тот минимум данных, который нужен, чтобы приложение работало, чтобы вы могли войти в свой аккаунт и чтобы ваш контент синхронизировался между вашими устройствами.

В этом документе описано, **какие** данные мы собираем, **зачем**, **где** они хранятся и **какие у вас права**.

## 2. Какие данные мы собираем

### 2.1 Данные аккаунта (при регистрации или входе)
| Данные | Источник | Зачем |
|---|---|---|
| Email | Вы (регистрация / Google Sign-In) | Идентификатор аккаунта, вход, восстановление |
| Пароль (в виде хэша) | Вы (регистрация по email) | Аутентификация. Открытый пароль мы не храним. |
| Имя | Вы / профиль Google | Отображение в интерфейсе |
| Google ID token | Google Sign-In | Одноразовая проверка вашей Google-личности, после чего токен отбрасывается |
| Сессионный токен | Наш сервер | Чтобы вы оставались в аккаунте между запусками |

### 2.2 Пользовательский контент (синхронизируется на наш сервер, если вы вошли в аккаунт)
| Данные | Зачем |
|---|---|
| Заметки (заголовок, тело, категория, цвет, даты) | Хранение и синхронизация заметок между устройствами |
| Задачи и пункты задач (текст, статус, срок, напоминания, повторы) | Хранение и синхронизация задач |
| События (заголовок, тело, категория, дата напоминания, повторы, подзадачи) | Хранение и синхронизация событий |
| Папки / категории, их порядок, цвет, видимость | Сохранение вашей организации между устройствами |
| Аудиозаписи, встроенные в заметки и события | Хранение и синхронизация голосовых заметок |

### 2.3 Технические данные
| Данные | Зачем |
|---|---|
| Версия приложения, имя пакета (`evonotes`) | Проверка версии, решение о soft/force обновлении |
| «Пинг» при запуске: анонимный идентификатор устройства (Android ID — свой у устройства и этого приложения, не рекламный идентификатор), модель устройства (производитель и модель, например «Google Pixel 9 Pro»), версия приложения, время запуска | Подсчёт установок и активных устройств (переустановка на том же телефоне не считается новым устройством), базовый мониторинг доступности, понимание, на каких устройствах работает приложение |
| «Пинг» при открытии веб-версии (evonotes.avzory.tech) после входа: ваш аккаунт, название браузера (например «Chrome», «Firefox»), версия приложения, время открытия. Android ID и модель устройства на сайте не собираются | Подсчёт пользователей сайта (первый вход на сайт — установка, следующие — входы), понимание, в каких браузерах работает сайт |
| Состояние системного разрешения на уведомления | Показ локальных напоминаний для событий и задач |

Мы **не** собираем: точное местоположение, контакты, рекламные идентификаторы, историю браузера, аудио с микрофона вне записей, которые вы делаете явно, аналитику нажатий внутри приложения.

### 2.4 Данные, которые остаются только на устройстве (нам не отправляются)
- Настройки приложения (тема, шрифт, язык, режим отображения, сортировка, сдвиг напоминания, состояние боковой панели) — `SharedPreferences`.
- Локальная копия всех заметок, задач и событий — локальная база SQLite (`sqflite`).
- Удалённые в корзину элементы, пока вы их не восстановили или не удалили окончательно.
- Запланированные локальные уведомления.
- События календарей телефона (Google Календарь, календарь Samsung, Outlook и другие, синхронизированные с устройством) — только если вы включите календари в меню вкладки «Календарь». Они читаются по разрешению Android «Календарь» исключительно для показа в EvoNotes: не копируются в приложение, не синхронизируются, не попадают в бэкап и не отправляются на наш сервер. Список выбранных календарей хранится на устройстве.

### 2.5 Синхронизация через Google Диск или Яндекс Диск (если вы её выбрали)

Вместо нашего сервера можно синхронизироваться через свой Google Диск или Яндекс Диск. Тогда:

- что записывается на ваш Диск: заметки, задачи, события, привычки, сессии учёта времени, папки, часть настроек (колонки канбана, функции, помодоро) и аудиозаписи, а также копии этих данных за последние 7 дней — для восстановления;
- где: на Google Диске — папка «EvoNotes», приложение видит только файлы, которые создало само (разрешение `drive.file`), остальные ваши файлы ему недоступны; на Яндекс Диске — папка «Приложения/EvoNotes»;
- подключение Диска одновременно выполняет вход в EvoNotes тем же аккаунтом: наш сервер получает email (и, для Google, имя), как описано в п. 2.1, а ваш контент передаётся по HTTPS напрямую между устройством и Диском и на наш сервер не отправляется;
- данные с вашего Диска используются только для синхронизации: не используются для рекламы, не продаются и не передаются третьим лицам. Использование и передача информации, полученной из API Google, соответствует [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), включая требования Limited Use;
- как отключить: выйдите из Диска в настройках синхронизации приложения; отозвать доступ приложения можно в любой момент на странице [myaccount.google.com/connections](https://myaccount.google.com/connections) или в настройках аккаунта Яндекса. Файлы на Диске остаются вашими — их можно удалить вручную.

## 3. Зачем мы собираем эти данные (правовое основание)

- **Исполнение договора** — без данных аккаунта и контента мы не сможем оказать услугу, на которую вы подписались.
- **Законный интерес** — проверка версии и анонимные пинги нужны, чтобы поддерживать стабильность сервиса и сообщать вам о важных обновлениях.
- **Согласие** — доступ к микрофону (для аудиозаметок), разрешение на уведомления и доступ к календарю (для показа календарей телефона) запрашиваются явно и могут быть отозваны в системных настройках в любой момент.

## 4. Где хранятся ваши данные

- **На вашем устройстве**: в приватном хранилище приложения (SQLite + SharedPreferences). Другие приложения не имеют к нему доступа.
- **На нашем сервере** (`avzory.tech`): запись об аккаунте и синхронизированная копия контента — пока существует ваш аккаунт.
- **На вашем Google Диске или Яндекс Диске**: если вы выбрали синхронизацию через диск (п. 2.5) — ваш контент и его копии за последние 7 дней, пока вы их не удалите.
- **Google / Firebase**: если вы используете вход через Google, Google аутентифицирует вас по своей политике конфиденциальности (https://policies.google.com/privacy). Мы получаем только email, имя и одноразовый ID token.
- **GitHub** (`Arty2904/Config`): там лежит **только** публичный конфиг обновлений (минимальная версия, ссылки на обновление, адрес сервера). Никакие пользовательские данные туда не отправляются.

## 5. Передача третьим лицам

Мы не продаём ваши данные и не передаём их рекламодателям.

Мы используем следующих обработчиков строго для работы сервиса:
- **Google Firebase Auth / Google Sign-In** — только аутентификация.
- **Наш хостинг-провайдер** — для работы сервера синхронизации.

Раскрытие данных возможно только если этого требует применимое законодательство (например, законный запрос уполномоченного органа).

## 6. Сроки хранения

- Аккаунт и синхронизированный контент — до удаления аккаунта или вашего запроса на удаление.
- Локальные данные на устройстве — до удаления приложения или очистки его данных.
- Корзина — локально, до её очистки.
- Серверные логи (метаданные запросов) — короткий срок для диагностики, затем ротируются.

## 7. Ваши права

В любой момент вы можете:
- **Получить доступ** к своим данным — прямо в приложении.
- **Изменить / удалить** любую заметку, задачу или событие.
- **Выйти из аккаунта** — токен сессии будет удалён с устройства. Локальная копия останется до тех пор, пока вы её не очистите.
- **Удалить аккаунт** — напишите на evonotes@avzory.com, мы удалим аккаунт и синхронизированный контент с сервера.
- **Отозвать разрешения** — микрофон, уведомления и доступ к календарю отзываются в системных настройках устройства.

В зависимости от юрисдикции (например, GDPR / 152-ФЗ) у вас также может быть право подать жалобу в надзорный орган по защите персональных данных.

## 8. Безопасность

- Пароли хранятся только в виде солёных хэшей на сервере.
- Связь с сервером — по HTTPS.
- Сессионный токен хранится в приватном хранилище приложения, изолированном от других приложений.
- Локальный контент хранится в песочнице приложения, предоставляемой Android.

Ни одна система не защищена на 100%; ответственность за доступ к вашему устройству несёте вы.

## 9. Дети

EvoNotes не предназначено для детей младше 13 лет. Мы сознательно не собираем данные у детей. Если вы считаете, что ребёнок передал нам данные, свяжитесь с нами — мы их удалим.

## 10. Изменения политики

Мы можем периодически обновлять эту политику. «Дата вступления в силу» в начале документа отражает актуальную версию. О существенных изменениях мы сообщим внутри приложения.

## 11. Контакты

Вопросы, запросы и жалобы: **evonotes@avzory.com**
