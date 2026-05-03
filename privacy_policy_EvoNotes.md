# Privacy Policy

**Application:** EvoNotes
**Package:** `com.avzory.EvoNotes`
**Effective date:** 2026-05-03
**Contact:** support@avzory.tech

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
| Anonymous "ping" on app start | Counting active installations, basic availability monitoring |
| OS-level notification permission state | Showing local reminders for events and to-dos |

We do **not** collect: precise location, contacts, advertising identifiers, browsing history, microphone audio outside of recordings you explicitly create, or analytics about how you tap inside the app.

### 2.4 Data stored only on your device (never sent to us)
- App settings (theme, font, language, view mode, sort order, reminder offset, sidebar state) — stored in `SharedPreferences`.
- A local copy of all your notes, to-dos, and events — stored in a local SQLite database (`sqflite`).
- Soft-deleted items in the trash, until you restore or permanently delete them.
- Scheduled local notifications.

## 3. Why We Collect This Data (Legal Basis)

- **Performance of a contract** — we need your account data and content to actually provide the service you signed up for.
- **Legitimate interest** — version checks and anonymous pings help us keep the service stable and notify you about important updates.
- **Consent** — microphone access (for audio notes) and notification permission are requested explicitly and can be revoked at any time in your device settings.

## 4. Where Your Data Is Stored

- **On your device**: in the app's private storage (SQLite + SharedPreferences). Other apps cannot read it.
- **On our server** (`avzory.tech`, EU/Russia region): account record and a synced copy of your content, kept while your account exists.
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
- **Access / export** your data — using the in-app export feature.
- **Edit / delete** any note, to-do, or event individually.
- **Sign out** — removes your session token from the device. Your local copy remains until you choose to clear it.
- **Delete your account** — write to support@avzory.tech; we will remove your account and synced content from our server.
- **Revoke permissions** — microphone and notifications can be revoked in your device's system settings.

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

Questions, requests, or complaints: **support@avzory.tech**

---
---

# Политика конфиденциальности

**Приложение:** EvoNotes
**Идентификатор пакета:** `com.avzory.EvoNotes`
**Дата вступления в силу:** 2026-05-03
**Контакт:** support@avzory.tech

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
| Анонимный «пинг» при запуске | Подсчёт активных установок, базовый мониторинг доступности |
| Состояние системного разрешения на уведомления | Показ локальных напоминаний для событий и задач |

Мы **не** собираем: точное местоположение, контакты, рекламные идентификаторы, историю браузера, аудио с микрофона вне записей, которые вы делаете явно, аналитику нажатий внутри приложения.

### 2.4 Данные, которые остаются только на устройстве (нам не отправляются)
- Настройки приложения (тема, шрифт, язык, режим отображения, сортировка, сдвиг напоминания, состояние боковой панели) — `SharedPreferences`.
- Локальная копия всех заметок, задач и событий — локальная база SQLite (`sqflite`).
- Удалённые в корзину элементы, пока вы их не восстановили или не удалили окончательно.
- Запланированные локальные уведомления.

## 3. Зачем мы собираем эти данные (правовое основание)

- **Исполнение договора** — без данных аккаунта и контента мы не сможем оказать услугу, на которую вы подписались.
- **Законный интерес** — проверка версии и анонимные пинги нужны, чтобы поддерживать стабильность сервиса и сообщать вам о важных обновлениях.
- **Согласие** — доступ к микрофону (для аудиозаметок) и разрешение на уведомления запрашиваются явно и могут быть отозваны в системных настройках в любой момент.

## 4. Где хранятся ваши данные

- **На вашем устройстве**: в приватном хранилище приложения (SQLite + SharedPreferences). Другие приложения не имеют к нему доступа.
- **На нашем сервере** (`avzory.tech`): запись об аккаунте и синхронизированная копия контента — пока существует ваш аккаунт.
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
- **Получить / экспортировать** свои данные — через встроенную функцию экспорта.
- **Изменить / удалить** любую заметку, задачу или событие.
- **Выйти из аккаунта** — токен сессии будет удалён с устройства. Локальная копия останется до тех пор, пока вы её не очистите.
- **Удалить аккаунт** — напишите на support@avzory.tech, мы удалим аккаунт и синхронизированный контент с сервера.
- **Отозвать разрешения** — микрофон и уведомления отзываются в системных настройках устройства.

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

Вопросы, запросы и жалобы: **support@avzory.tech**
