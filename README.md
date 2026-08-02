<!-- Animated Wave Header - Blue/Purple Gradient -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0138b7,50:3d53d7,100:5372e0&height=180&section=header&text=NOTHING&fontSize=60&fontColor=b8ceff&animation=fadeIn&fontAlignY=35&desc=By%20VexCrux&descSize=18&descAlignY=55&descColor=a1b9f6" alt="Header">

<!-- Language Switcher -->
<p align="center">
  <img src="https://img.shields.io/badge/🇷🇺_Русский-Active-2ea44f?style=plastic&logo=googletranslate&logoColor=white" alt="Russian">
  <img src="https://img.shields.io/badge/🇬🇧_English-Active-2ea44f?style=plastic&logo=googletranslate&logoColor=white" alt="English">
</p>

<!-- Browser Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white&style=plastic" alt="Chrome">
  <img src="https://img.shields.io/badge/Edge-Extension-0078D7?logo=microsoftedge&logoColor=white&style=plastic" alt="Edge">
  <img src="https://img.shields.io/badge/Brave-Extension-FB542B?logo=brave&logoColor=white&style=plastic" alt="Brave">
  <img src="https://img.shields.io/badge/Version-0.2.2-3d53d7?style=plastic" alt="Version">
  <img src="https://img.shields.io/badge/Status-Beta-FB542B?style=plastic" alt="Status">
</p>

<!-- Description -->
<p align="center"><b>Advanced Browser Privacy & Digital Fingerprint Management</b></p>
<p align="center"><i>Продвинутая защита конфиденциальности и управление цифровым отпечатком браузера</i></p>

<!-- Author -->
<p align="center">
  <a href="https://github.com/VexCrux">
    <img src="https://img.shields.io/badge/by-VexCrux-3d53d7?style=plastic&logo=github&logoColor=white" alt="VexCrux"/>
  </a>
</p>

<!-- Quick Stats -->
<p align="center">
  <a href="https://github.com/VexCrux/Nothing.Expansion/stargazers">
    <img src="https://img.shields.io/github/stars/VexCrux/Nothing.Expansion?style=plastic&logo=github&label=Stars" alt="Stars"/>
  </a>
  <a href="https://github.com/VexCrux/Nothing.Expansion/network/members">
    <img src="https://img.shields.io/github/forks/VexCrux/Nothing.Expansion?style=plastic&logo=github&label=Forks" alt="Forks"/>
  </a>
  <a href="https://github.com/VexCrux/Nothing.Expansion/releases">
    <img src="https://img.shields.io/github/downloads/VexCrux/Nothing.Expansion/total?style=plastic&logo=github&label=Downloads" alt="Downloads"/>
  </a>
  <img src="https://img.shields.io/github/last-commit/VexCrux/Nothing.Expansion?style=plastic&logo=github&label=Last+Commit" alt="Last Commit"/>
</p>

<!-- Quick Navigation -->
<p align="center">
  <a href="#-features--возможности">✨ Features</a> •
  <a href="#-installation--установка">🚀 Install</a> •
  <a href="#-timezone-showcase--часовые-пояса">🌍 Timezones</a> •
  <a href="#-roadmap--планы-развития">🗺️ Roadmap</a>
</p>

---

## ⚠️ Disclaimer / Предупреждение

> [!WARNING]
> **EN:** This extension is built **exclusively** for privacy protection, digital fingerprint management, and network traffic analysis. **Always use official builds from this repository.**
>
> **RU:** Расширение создано **исключительно** для защиты конфиденциальности, управления цифровыми отпечатками и анализа сетевого трафика. **Используйте только официальные сборки из этого репозитория.**

---

## ✨ Features / Возможности

### 📊 Traffic Monitor — Реальный мониторинг трафика

> Встроенная панель статистики вкладки в реальном времени.

| Metric / Метрика | EN Description | RU Описание |
|---|---|---|
| **Domain** | Current tab domain being monitored | Текущий домен активной вкладки |
| **Requests** | Total HTTP requests count | Общее количество HTTP-запросов |
| **Packet Loss** | Percentage of lost/blocked packets | Процент потерь и заблокированных пакетов |
| **Traffic Volume** | Data transferred (KB/MB) | Объём переданных данных (КБ/МБ) |
| **Blocked Trackers** | Count of tracker scripts blocked | Количество заблокированных трекеров |
| **Session Timer** | Active protection duration | Время активной защиты сессии |
| **Total Protected** | Cumulative protection time | Общее время под защитой |

---

### 🔧 Core Protection Features / Основные функции защиты

| # | 🏷️ Feature (EN) | 🏷️ Возможность (RU) | Status | 📋 Description / Описание |
|---|------------------|----------------------|--------|---------------------------|
| 1 | **Master Toggle** | **Общий выключатель** | ✅ | Instant on/off switch. Settings bypass browser service pages. / Мгновенное включение/выключение. Настройки не действуют на служебных страницах браузера. |
| 2 | **Browser Identification** | **Идентификация браузера** | ✅ | Spoofs User-Agent, platform, and OS simultaneously. Selectable profiles: Windows 11 · Chrome, macOS · Safari, Linux · Firefox and more. / Подменяет User-Agent, платформу и ОС одновременно. Выбор профилей: Windows 11 · Chrome, macOS · Safari, Linux · Firefox и другие. |
| 3 | **System Spoofing** | **Подмена системы** | ✅ | Simultaneously spoofs User-Agent + platform + WebGL renderer string. / Одновременная подмена User-Agent + платформы + строки WebGL-рендерера. |
| 4 | **Hardware Parameters** | **Аппаратные параметры** | ✅ | Masks hardware-level browser metrics: CPU cores, device memory, etc. / Маскировка аппаратных данных: ядра CPU, память устройства и др. |
| 5 | **Screen Resolution** | **Разрешение экрана** | ✅ | Changes only `screen.width`/`screen.height` for fingerprinting — doesn't resize the window, so site layout stays intact. / Меняет только `screen.width`/`screen.height` (для фингерпринта) — не трогает размер окна, поэтому вёрстка не ломается. |
| 6 | **Canvas & Audio Noise** | **Canvas/Audio шум** | ✅ | Injects subtle randomization into Canvas and AudioContext APIs to prevent fingerprinting without breaking sites. / Добавляет рандомизацию в Canvas и AudioContext API для защиты от фингерпринтинга без поломки сайтов. |
| 7 | **Adaptive Noise Aggression** | **Адаптивная агрессия шума** | ✅ | Dynamically scales noise intensity based on how aggressively a site attempts fingerprinting. / Динамически масштабирует интенсивность шума в зависимости от агрессивности трекеров на сайте. |
| 8 | **Real-time WebGL Spoofing** | **Подмена WebGL (real-time)** | ✅ | Spoofs WebGL renderer and vendor strings in real-time. / Подменяет строки рендерера и вендора WebGL в реальном времени. |
| 9 | **Anti-fraud / Geo-tracker Blocking** | **Блокировка антифрод/geo-трекеров** | ✅ | Blocks known anti-fraud and geographic tracking scripts. / Блокирует известные антифрод-скрипты и гео-трекеры. |
| 10 | **WebRTC IP-Leak Block** | **Блокировка WebRTC IP-leak** | ✅ | Prevents real IP leaks via WebRTC with per-site whitelist support. / Блокирует утечку реального IP через WebRTC с поддержкой белого списка сайтов. |
| 11 | **Timezone Spoofing** | **Подмена часового пояса** | ⚠️ Beta | Spoof timezone to any location, or auto-sync with your IP. Known issue: minor UI alignment bugs in the timezone selector field. / Подмена таймзоны под любую локацию или автонастройка по IP. Известный баг: небольшое смещение элементов в поле выбора часового пояса. |
| 12 | **TURN Server Configuration** | **Настройка TURN-сервера** | ⚠️ Beta | Custom TURN server for WebRTC relay. Warning dialog appears when all fields are filled. Known issue: dialog timing needs refinement. / Пользовательский TURN-сервер для WebRTC-ретрансляции. Диалог предупреждения при заполнении всех полей. Известный баг: тайминг диалога требует доработки. |

---

### 🔍 Anonymity Check — Проверка анонимности

> Built-in fingerprint verification panel showing what your browser actually exposes to websites.

<details>
<summary>📖 What is checked / Что проверяется</summary>

| Check / Проверка | Description / Описание |
|---|---|
| **User-Agent** | Is your UA spoofed correctly? / Корректно ли подменён UA? |
| **Platform** | Does navigator.platform match spoofed OS? / Соответствует ли platform подменённой ОС? |
| **WebGL Renderer** | Is GPU info masked? / Скрыта ли информация о GPU? |
| **Canvas Fingerprint** | Is canvas noise applied? / Применён ли шум canvas? |
| **Audio Fingerprint** | Is audio context randomized? / Рандомизирован ли AudioContext? |
| **WebRTC** | Is real IP leaking? / Утечка реального IP? |
| **Timezone** | Does timezone match IP geolocation? / Соответствует ли часовой пояс IP-геолокации? |
| **Screen Resolution** | Is screen resolution spoofed? / Подменено ли разрешение? |
| **Hardware Concurrency** | Is CPU core count masked? / Скрыто ли количество ядер? |
| **Device Memory** | Is RAM info spoofed? / Подменена ли информация о RAM? |

</details>

---

### 🔄 Compatibility Tab — Вкладка совместимости

> Extension compatibility checker — detects other installed privacy extensions and identifies potential conflicts.

| Feature / Функция | Status | Description / Описание |
|---|---|---|
| **Extension Detection** | 🔜 Planned | Detect installed extensions (uBlock Origin, Privacy Badger, Decentraleyes, WebRTC disablers, etc.) |
| **Conflict Analysis** | 🔜 Planned | Identify duplicate protections and recommend which to keep |
| **Version Display** | 🔜 Planned | Show detected extension versions |
| **Auto-Repair** | 🔜 Planned | Attempt automatic conflict resolution; stop after 2 failed attempts; continue blocking site-originated threats regardless |

---

## 🚀 Installation / Установка

| Step | 📝 Action (EN) | 📝 Действие (RU) |
|------|---------------|------------------|
| **1** | Click **Code** → **Download ZIP** | Нажмите **Code** → **Download ZIP** |
| **2** | Extract ZIP to a dedicated folder | Распакуйте архив в отдельную папку |
| **3** | Open browser → `chrome://extensions/` | Откройте браузер → `chrome://extensions/` |
| **4** | Enable **Developer mode** (top-right toggle) | Включите **Режим разработчика** (переключатель справа вверху) |
| **5** | Click **Load unpacked** → select project folder | Нажмите **Загрузить распакованное** → выберите папку проекта |

> 💡 **EN:** Pin the extension icon to your toolbar for instant access.
> 💡 **RU:** Закрепите иконку расширения на панели инструментов для быстрого доступа.

---

## 🌍 Timezone Showcase / Часовые пояса

<div align="center">

| 🌍 Region / Регион | 🌆 City / Город | 📝 Location Details / Описание локации |
| :--- | :--- | :--- |
| 🇺🇸 **Americas** | `America/New_York` | East Coast USA Time / Время восточного побережья США |
| 🇬🇧 **Europe** | `Europe/London` | Greenwich Mean Time (GMT) / Среднее время по Гринвичу |
| 🇷🇺 **Europe** | `Europe/Moscow` | Moscow Standard Time (MSK) / Московское стандартное время |
| 🇯🇵 **Asia** | `Asia/Tokyo` | Japan Standard Time (JST) / Стандартное время Японии |
| 🇦🇪 **Asia** | `Asia/Dubai` | Gulf Standard Time (GST) / Стандартное время Персидского залива |
| 🌐 **Global** | **+ 50 More...** | **And many more... / И многие другие...** |

<br>

> 🔄 **Auto-detect from IP** — Automatically sync your timezone with your real IP location to avoid detection.
>
> 🔄 **Автонастройка по реальному IP** — Автоматически определит часовой пояс вашего текущего IP и выставит его. Так рассинхрон станет невозможен в принципе.

</div>

---

## 🗺️ Roadmap / Планы развития

<div align="center">

| Status | Feature / Функция |
|:------:|---|
| ✅ | Traffic monitor with real-time stats |
| ✅ | User-Agent / Platform / WebGL spoofing |
| ✅ | Canvas & Audio fingerprint noise |
| ✅ | Adaptive noise aggression |
| ✅ | WebRTC IP-leak prevention + whitelist |
| ✅ | Timezone spoofing + IP auto-sync |
| ✅ | TURN server configuration |
| ✅ | Built-in anonymity check panel |
| 🔧 | Fix timezone field UI alignment |
| 🔧 | Fix TURN server warning dialog timing |
| 🔧 | Remove "(обновлено)" badge from Fingerprint section |
| 🔜 | Compatibility tab: detect installed extensions |
| 🔜 | Compatibility tab: version display for detected extensions |
| 🔜 | Activity logs panel with filtering |
| 🔜 | Auto-repair engine (max 2 attempts, then stop) |
| 🔜 | OS icon spoofing (Windows version fingerprint) |
| 🔜 | Smooth tab transitions (Трафик ↔ Совместимость) |

</div>

---

## ⚙️ Tech Stack

<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=plastic&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=plastic&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=plastic&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Chrome%20API-Manifest%20V3-4285F4?style=plastic&logo=googlechrome&logoColor=white" alt="Chrome API">
  <img src="https://img.shields.io/badge/WebRTC-API-333333?style=plastic&logo=webrtc&logoColor=white" alt="WebRTC">
</p>

</div>

---

## 🛡️ Security Notes / Примечания по безопасности

| 🔒 Feature / Функция | 🎯 Why It Matters / Зачем это нужно |
|----------------------|--------------------------------------|
| **Canvas & Audio Noise** | Adds subtle randomization to prevent fingerprinting without breaking sites. / Добавляет рандомизацию для защиты от фингерпринтинга без поломки сайтов. |
| **WebRTC IP-Leak Block** | Essential for VPN users — stops real IP leaks during P2P connections. / Критично для VPN-пользователей — блокирует утечку IP в P2P-соединениях. |
| **Adaptive Aggression** | Scales protection based on how aggressively a site tries to fingerprint you. / Масштабирует агрессивность шума в зависимости от трекеров на сайте. |
| **Auto Timezone Sync** | Eliminates timezone/IP mismatch. A mismatch exposes you stronger than having no spoofing at all. / Подмена должна совпадать с реальным IP (или VPN), иначе рассинхрон выдаст вас сильнее, чем отсутствие подмены. |
| **TURN Server Relay** | Routes WebRTC through a trusted relay, hiding your real IP even from STUN requests. / Маршрутизирует WebRTC через доверенный релей, скрывая реальный IP даже от STUN-запросов. |

---

## 📝 Changelog / История изменений

### v0.2.2 (Current — Beta)
- ✅ Added TURN server configuration panel
- ✅ Added built-in anonymity check (fingerprint verification)
- ✅ Added adaptive noise aggression slider
- ✅ Improved traffic monitor with session timer
- ⚠️ Known issue: timezone field UI alignment
- ⚠️ Known issue: TURN server warning dialog timing

### v0.2.1
- ✅ Added timezone spoofing with IP auto-sync
- ✅ Added screen resolution spoofing (non-destructive)
- ✅ Added hardware parameters masking
- ✅ Added anti-fraud/geo-tracker blocking

### v0.2.0
- ✅ Initial public beta release
- ✅ Core fingerprint protection (Canvas, Audio, WebGL)
- ✅ WebRTC IP-leak prevention
- ✅ User-Agent and system spoofing
- ✅ Traffic monitor panel

---

<div align="center">

<!-- Animated Wave Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5372e0,50:3d53d7,100:0138b7&height=120&section=footer" alt="Footer">

<p><b>Nothing — stay invisible.</b></p>
<p>
  <sub>⭐ Star this repo if Nothing helps you stay private!</sub>
</p>

</div>
