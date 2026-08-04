<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0138b7,50:3d53d7,100:5372e0&height=160&section=header&text=Nothing&fontSize=45&fontColor=b8ceff&desc=Browser+Privacy+%26+Fingerprint+Management&descSize=16&descAlignY=60" alt="Header">

<p align="center">
  <strong>Advanced Browser Privacy & Digital Fingerprint Management</strong><br>
  <strong>Продвинутое управление цифровыми отпечатками и защита конфиденциальности</strong>
</p>

<p align="center">
  <a href="https://github.com/VexCrux/Nothing.Expansion/releases"><img src="https://img.shields.io/badge/Version-0.2.3-3d53d7?style=flat-square" alt="Version"></a>
  <a href="https://github.com/VexCrux/Nothing.Expansion/stargazers"><img src="https://img.shields.io/github/stars/VexCrux/Nothing.Expansion?style=flat-square&logo=github" alt="Stars"></a>
  <a href="https://github.com/VexCrux/Nothing.Expansion/network/members"><img src="https://img.shields.io/github/forks/VexCrux/Nothing.Expansion?style=flat-square&logo=github" alt="Forks"></a>
  <a href="https://github.com/VexCrux/Nothing.Expansion/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" alt="License"></a>
</p>

<p align="center">
  <a href="#-warning--предупреждение">⚠️ Warning</a> •
  <a href="#-features--возможности">✨ Features</a> •
  <a href="#-installation--установка">Installation</a> •
  <a href="#-timezones--часовые-пояса">Timezones</a> •
  <a href="#-security">Security</a> •
  <a href="https://github.com/VexCrux/Nothing.Expansion/discussions/1">Discussions</a>
</p>

---

## ⚠️ Important Warning

> [!CAUTION]
> **Nothing does NOT provide 100% anonymity** — This extension works only at browser level and **does NOT hide your real IP address**. For real anonymity, use **VPN or Tor** separately.

> [!IMPORTANT]
> **Desync is worse than no protection** — If the spoofed timezone doesn't match your real IP geolocation, this is **more noticeable** to trackers than no spoofing at all.

> [!NOTE]
> **Technical limitations** — Browsers don't allow extensions to hide everything. Nothing protects where technically possible, but cannot guarantee complete invisibility.

---

## ⚠️ Важное предупреждение

> [!WARNING]
> **Nothing не даёт 100% анонимности** — Это расширение работает только на уровне браузера и **не скрывает ваш реальный IP-адрес**. Для настоящей анонимности используйте **VPN или Tor** отдельно.

> [!IMPORTANT]
> **Рассинхрон хуже отсутствия защиты** — Если подменный часовой пояс не совпадает с вашей реальной геолокацией по IP, это **более заметно** трекерам, чем вообще никакая подмена.

> [!NOTE]
> **Технические ограничения** — Браузер не позволяет расширениям скрыть всё. Nothing защищает там, где это технически возможно, но не может гарантировать полную невидимость.

---

## What Nothing Does NOT Do

| ❌ Does NOT do | ✅ Does |
|----------------|---------|
| Hide your real IP address | Spoof User-Agent and platform |
| Replace VPN/proxy | Mask Canvas and Audio fingerprint |
| Provide 100% anonymity guarantee | Block WebRTC IP-leaks |
| Hide your browsing history | Spoof timezone |
| Hide your behavior | Monitor traffic in real-time |

---

## Что Nothing НЕ делает

| ❌ Не делает | ✅ Делает |
|-------------|----------|
| Скрывает ваш реальный IP-адрес | Подменяет User-Agent и платформу |
| Заменяет VPN/прокси | Маскирует Canvas и Audio fingerprint |
| Даёт 100% гарантии анонимности | Блокирует WebRTC IP-leaks |
| Скрывает историю посещений | Подменяет часовой пояс |
| Скрывает ваше поведение | Мониторит трафик в реальном времени |

---

## ✨ Features

### 📊 Traffic Monitor

Built-in statistics panel for active tab:

| Metric | Description |
|--------|-------------|
| **Domain** | Currently monitored page |
| **Requests** | Total HTTP requests count |
| **Traffic** | Data transferred (KB/MB) |
| **Blocked** | Number of blocked trackers |
| **Session** | Active protection time (timer) |

---

## ✨ Возможности

### 📊 Мониторинг трафика

Встроенная панель статистики по активной вкладке:

| Метрика | Описание |
|---------|----------|
| **Домен** | Текущая отслеживаемая страница |
| **Запросы** | Общее количество HTTP-запросов |
| **Трафик** | Объём переданных данных (КБ/МБ) |
| **Блокировки** | Количество заблокированных трекеров |
| **Сессия** | Время активной защиты (таймер) |

---

### 🔧 Fingerprint Protection

| Feature | Description |
|---------|-------------|
| **User-Agent spoofing** | UA + platform + OS spoofed simultaneously |
| **System profiles** | Windows 10/11, macOS, Linux with custom profiles |
| **Canvas/Audio noise** | Deterministic noise with unique hash per site |
| **WebGL spoofing** | Renderer and vendor spoofing in real-time |
| **Hardware parameters** | Masks CPU cores, device memory |
| **Screen resolution** | Changes `screen.width/height` without resizing window |

---

### 🔧 Защита от fingerprinting

| Функция | Описание |
|---------|----------|
| **User-Agent спуфинг** | Подмена UA + платформы + ОС одновременно |
| **Профили систем** | Windows 10/11, macOS, Linux с кастомными профилями |
| **Canvas/Audio шум** | Детерминированный шум с уникальным хэшем на сайт |
| **WebGL спуфинг** | Подмена рендерера и вендора в реальном времени |
| **Аппаратные параметры** | Маскировка CPU cores, device memory |
| **Разрешение экрана** | Меняет `screen.width/height` без изменения окна |

---

### 🌐 Network Security

| Feature | Description |
|---------|-------------|
| **WebRTC IP-leak block** | Blocks IP leak via WebRTC with whitelist |
| **Anti-fraud trackers** | Blocks known anti-fraud and geo-tracking services |
| **Timezone spoofing** | Full IANA timezone list with auto-sync by IP |
| **Do Not Track** | Sends DNT signal (disabled by default) |
| **TURN server** | Custom WebRTC relay configuration with confirmation |

---

### 🌐 Сетевая безопасность

| Функция | Описание |
|---------|----------|
| **WebRTC IP-leak блок** | Блокировка утечки IP через WebRTC с whitelist |
| **Антифрод-трекеры** | Блокировка известных антифрод и geo-tracking сервисов |
| **Подмена часового пояса** | Полный список IANA-таймзон с автонастройкой по IP |
| **Do Not Track** | Отправка сигнала DNT (выключено по умолчанию) |
| **TURN-сервер** | Кастомная настройка WebRTC relay с подтверждением |

---

### 🔍 Compatibility

| Extension | Status | Note |
|-----------|--------|------|
| **Brave Shields** | ℹ️ Works together | Built-in Brave protection + Nothing independent |
| **uBlock Origin** | ✅ Compatible | Works without conflicts |
| **Privacy Badger** | ✅ Compatible | Adaptive aggression reduces conflicts |
| **Decentraleyes** | ✅ Compatible | No functionality overlap |

> Nothing automatically softens Canvas noise when detecting similar privacy tools to prevent conflicts.

---

### 🔍 Совместимость

| Расширение | Статус | Примечание |
|------------|--------|------------|
| **Brave Shields** | ℹ️ Работает вместе | Встроенная защита Brave + Nothing независимы |
| **uBlock Origin** | ✅ Совместимо | Работает без конфликтов |
| **Privacy Badger** | ✅ Совместимо | Adaptive aggression снижает конфликт |
| **Decentraleyes** | ✅ Совместимо | Нет перекрытия функциональности |

> Nothing автоматически смягчает Canvas-шум при обнаружении похожих privacy-инструментов для предотвращения конфликтов.

---

## 🌍 Timezones

Full support for all IANA timezones with **live time display** (HH:MM:SS).

### Popular timezones:

| Region | City | Timezone ID |
|--------|------|-------------|
| 🇷🇺 Russia | Moscow | `Europe/Moscow` |
| 🇷🇺 Russia | Yekaterinburg | `Asia/Yekaterinburg` |
| 🇷🇺 Russia | Novosibirsk | `Asia/Novosibirsk` |
| 🇬🇧 Europe | London | `Europe/London` |
| 🇩🇪 Europe | Berlin | `Europe/Berlin` |
| 🇺🇸 USA | New York | `America/New_York` |
| 🇺🇸 USA | Los Angeles | `America/Los_Angeles` |

> **IP Auto-sync:** One click — automatic timezone detection based on your current IP. Eliminates desync between geolocation and time.

---

## 🌍 Часовые пояса

Полная поддержка всех IANA-таймзон с **живым отображением времени** (ЧЧ:ММ:СС).

### Популярные пояса:

| Регион | Город | Timezone ID |
|--------|-------|-------------|
| 🇷🇺 Россия | Москва | `Europe/Moscow` |
| 🇷🇺 Россия | Екатеринбург | `Asia/Yekaterinburg` |
| 🇷🇺 Россия | Новосибирск | `Asia/Novosibirsk` |
| 🇬🇧 Европа | Лондон | `Europe/London` |
| 🇩🇪 Европа | Берлин | `Europe/Berlin` |
| 🇺🇸 США | Нью-Йорк | `America/New_York` |
| 🇺🇸 США | Лос-Анджелес | `America/Los_Angeles` |

> **Автонастройка по IP:** Один клик — автоматическое определение часового пояса по вашему текущему IP. Исключает рассинхрон между геолокацией и временем.

---

## 🚀 Installation

| Step | Action |
|------|--------|
| **1** | Download ZIP: [Code → Download ZIP](https://github.com/VexCrux/Nothing.Expansion/archive/refs/heads/main.zip) |
| **2** | Extract archive to separate folder |
| **3** | Open `chrome://extensions/` or `brave://extensions/` |
| **4** | Enable **Developer mode** (toggle top-right) |
| **5** | Click **Load unpacked** → select project folder |
| **6** | Pin icon to toolbar for quick access |

---

## 🚀 Установка

| Шаг | Действие |
|-----|----------|
| **1** | Скачайте ZIP: [Code → Download ZIP](https://github.com/VexCrux/Nothing.Expansion/archive/refs/heads/main.zip) |
| **2** | Распакуйте архив в отдельную папку |
| **3** | Откройте `chrome://extensions/` или `brave://extensions/` |
| **4** | Включите **Режим разработчика** (toggle справа вверху) |
| **5** | Нажмите **Load unpacked** → выберите папку проекта |
| **6** | Закрепите иконку на панели инструментов для быстрого доступа |

---

## 🛡️ Security

### Architecture

nothing/ ├── manifest.json — Config (Manifest V3) ├── background.js — Service Worker: headers, blocking, stats ├── content-loader.js — Injects inject.js into page ├── inject.js — Main World: navigator/canvas/webgl/timezone spoofing ├── popup.html/js — Extension interface └── icons/ — Extension icons


### Privacy Policy

| Not stored | Why this matters |
|------------|------------------|
| No personal data | Extension doesn't collect information about you |
| No telemetry | No external API — data stays local |
| No analytics | No tracking usage |
| No history | Only current session in memory |

> [!TIP]
> All data is stored **locally in browser** and never transmitted anywhere. Check source code — everything is open on GitHub.

---

## 🛡️ Безопасность

### Архитектура

nothing/ ├── manifest.json — Config (Manifest V3) ├── background.js — Service Worker: заголовки, блокировка, статистика ├── content-loader.js — Внедряет inject.js в страницу ├── inject.js — Main World: подмена navigator/canvas/webgl/timezone ├── popup.html/js — Интерфейс расширения └── icons/ — Иконки расширения


### Политика конфиденциальности

| Не сохраняется | Почему это важно |
|----------------|------------------|
| Никакие личные данные | Расширение не собирает информацию о вас |
| Никакая телеметрия | Нет внешнего API — данные остаются локально |
| Никакая аналитика | Нет трекинга использования |
| Никакая история | Только текущая сессия в памяти |

> [!TIP]
> Все данные хранятся **локально в браузере** и нигде не передаются. Проверьте исходный код — всё открыто на GitHub.

---

## 📝 Releases

All releases available at: **[View Releases →](https://github.com/VexCrux/Nothing.Expansion/releases)**

| Version | Status | Key Updates |
|---------|--------|-------------|
| **v0.2.3** | Stable | Live clock, compatibility tab, extended timezones |
| **v0.2.2** | Stable | TURN server config, fingerprint verification |
| **v0.2.1** | Stable | Timezone spoofing, hardware masking |
| **v0.2.0** | Beta | Initial public release |

---

## 📝 Релизы

Все религи доступны здесь: **[Посмотреть релизы →](https://github.com/VexCrux/Nothing.Expansion/releases)**

| Версия | Статус | Основные обновления |
|--------|--------|---------------------|
| **v0.2.3** | Stable | Живые часы, вкладка совместимости, расширенные таймзоны |
| **v0.2.2** | Stable | Настройка TURN, проверка отпечатка |
| **v0.2.1** | Stable | Подмена таймзоны, маскировка железа |
| **v0.2.0** | Beta | Первый публичный релиз |

---

## 🤝 Support

### Report a Bug

1. Open [Releases](https://github.com/VexCrux/Nothing.Expansion/releases)
2. Check if issue exists
3. If not, create issue with: browser, Nothing version, reproduction steps

### Request a Feature

1. Visit [Discussions](https://github.com/VexCrux/Nothing.Expansion/discussions/1)
2. Create new feature request thread
3. Describe use case and expected behavior

---

## 🤝 Поддержка

### Сообщить о баге

1. Откройте [Релизы](https://github.com/VexCrux/Nothing.Expansion/releases)
2. Проверьте наличие существующего issue
3. Если нет — создайте с указанием: браузер, версия Nothing, шаги воспроизведения

### Предложить функцию

1. Посетите [Обсуждения](https://github.com/VexCrux/Nothing.Expansion/discussions/1)
2. Создайте новую тему с просьбой о фиче
3. Опишите use case и ожидаемое поведение

---

## 💬 Questions & Feedback

Open a discussion thread: **[Join Discussion →](https://github.com/VexCrux/Nothing.Expansion/discussions/1)**

---

<div align="center">

<img src="https://capsule-web.com/api?type=waving&color=0:5372e0,50:3d53d7,100:0138b7&height=100&section=footer" alt="Footer">

<p><b>Nothing — stay invisible.</b></p>
<p>
  <a href="https://github.com/VexCrux/Nothing.Expansion/stargazers"><img src="https://img.shields.io/github/stars/VexCrux/Nothing.Expansion?style=social" alt="Star"></a>
  <sub>⭐ Star this repo if Nothing helps you stay private!</sub>
</p>

</div>
