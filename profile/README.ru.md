<div align="center">

<img src="https://raw.githubusercontent.com/team-ph4r0s/.github/main/profile/banner.svg" alt="Team Pharos — открытые инструменты для безопасности и приватности" width="100%">

<br>

<h1>Team Pharos</h1>

<p>
  <a href="https://github.com/team-ph4r0s/.github/blob/main/profile/README.md">🇬🇧 English</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/team-ph4r0s/.github/blob/main/profile/README.ru.md">🇷🇺 Русский</a>
</p>

<p>
  <strong>Открытые инструменты, которые освещают путь там, где важна приватность.</strong><br>
  Безопасность, приватность и полезная инфраструктура, которую можно запускать и понимать самостоятельно.
</p>

<p>
  <a href="https://github.com/orgs/team-ph4r0s/repositories"><img src="https://img.shields.io/badge/public_projects-4-14224a?style=for-the-badge&logo=github&logoColor=ffd978" alt="4 публичных проекта"></a>
  <a href="https://app.lava.top/pharosteam"><img src="https://img.shields.io/badge/support_pharos-Lava.top-ffd978?style=for-the-badge&logo=heart&logoColor=14224a" alt="Поддержать Pharos на Lava.top"></a>
</p>

</div>

## 🏛️ Наши принципы

Название Pharos отсылает к Александрийскому маяку: его видно издалека, он помогает пройти через сложные условия и нужен именно тогда, когда это важно. Мы создаём точечные open-source-инструменты для тех, кто хочет контролировать свои файлы, устройства и инфраструктуру.

- 🔓 **Открыто по умолчанию** — исходный код, шаги сборки и предположения о безопасности остаются видимыми.
- 🛡️ **Нулевое доверие** — непроверенные файлы и удалённые серверы считаются враждебными, пока не доказано обратное.
- 🏠 **Самостоятельное размещение там, где это важно** — данные, ключи и конфигурации остаются под вашим контролем.
- 📵 **Без скрытой телеметрии** — проекты рассчитаны на работу без тайных облачных зависимостей и отслеживания.

Ниже представлены **только публичные репозитории**.

## 🚀 Публичные проекты

| Проект | Что делает | Платформа / стек | Лицензия |
|:--|:--|:--|:--:|
| 🛡️ [**Arca**](https://github.com/team-ph4r0s/arca) | Проверяет и открывает подозрительные документы в одноразовой WebAssembly-песочнице, а затем создаёт очищенные копии. | Android · iOS · Rust · WebAssembly | AGPL-3.0-only |
| 🧠 [**dementia-panel**](https://github.com/team-ph4r0s/dementia-panel) | Управляет серверами AmneziaWG по SSH без установки агентов на серверах. | Linux · Docker · TypeScript · React | MIT |
| 🏢 [**land.inc**](https://github.com/team-ph4r0s/land.inc) | Превращает локальные сессии Claude Code, Codex и Antigravity в живой 2.5D-офис для наблюдения и совместной работы. | Windows · macOS · Linux · Node.js · PixiJS | См. репозиторий |
| 🎓 [**MPEI.Hub**](https://github.com/team-ph4r0s/mpei-next) | Помощник студента с приоритетом приватности: расписание МЭИ, БАРС, карта кампуса и офлайн-сценарии учёбы. | Android · iOS · Kotlin Multiplatform | MIT |

<br>

<table>
<tr>
<td colspan="2">

### 🛡️ [Arca](https://github.com/team-ph4r0s/arca)

**Параноидально безопасный просмотрщик и очиститель документов, которым нельзя доверять.** Arca разбирает файлы Office, OpenDocument, PDF, RTF, Outlook, Visio, Access и изображения в одноразовой WebAssembly-песочнице без доступа к сети, объясняет найденное и по возможности создаёт стерильную копию.

[![Safe Rust](https://img.shields.io/badge/Safe_Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://github.com/team-ph4r0s/arca)
[![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)](https://github.com/team-ph4r0s/arca)
[![Android](https://img.shields.io/badge/Android_8%E2%80%9316-34A853?style=flat-square&logo=android&logoColor=white)](https://github.com/team-ph4r0s/arca/blob/main/docs/ANDROID.md)
[![iOS](https://img.shields.io/badge/iOS_16%2B-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/team-ph4r0s/arca/blob/main/app/README.md)
[![Latest release](https://img.shields.io/github/v/release/team-ph4r0s/arca?style=flat-square&label=latest%20release&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/arca/releases/latest)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🦀 Безопасное управление памятью**<br>
<sub>Парсерный код написан на Rust с <code>#![forbid(unsafe_code)]</code> и строгими ресурсными ограничениями.</sub>

**🔬 Рентген угроз**<br>
<sub>Ищет макросы, скрипты, внешние шаблоны, трекинг-пиксели, опасные URI-схемы, скрытое содержимое и криминалистические метаданные.</sub>

</td>
<td width="50%" valign="top">

**📦 Одноразовая песочница**<br>
<sub>Wasm-гостю недоступны импорты, сеть, диск, часы и IPC. После анализа его память очищается.</sub>

**🧼 Стерильные копии**<br>
<sub>Удаляет активное содержимое и метаданные, перерисовывает растровые изображения в новые PNG и повторно проверяет результат.</sub>

</td>
</tr>
</table>

> ✅ **Честные вердикты:** статус `Clean` выдаётся только после распознавания каждого байта. Всё неоднозначное остаётся `Unverified`.

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/arca) &nbsp;·&nbsp;
[**📥 Скачать APK**](https://github.com/team-ph4r0s/arca/releases/latest) &nbsp;·&nbsp;
[Архитектура](https://github.com/team-ph4r0s/arca/blob/main/docs/ARCHITECTURE.md) &nbsp;·&nbsp;
[Модель угроз](https://github.com/team-ph4r0s/arca/blob/main/docs/SECURITY_THREAT_MODEL.md) &nbsp;·&nbsp;
[Полигон атак](https://github.com/team-ph4r0s/arca/blob/main/tests/malware-test/README.md) &nbsp;·&nbsp;
[iOS](https://github.com/team-ph4r0s/arca/blob/main/app/README.md) &nbsp;·&nbsp;
[Релизы](https://github.com/team-ph4r0s/arca/releases)

</div>

<br>

<table>
<tr>
<td colspan="2">

### 🧠 [dementia-panel](https://github.com/team-ph4r0s/dementia-panel)

**Безагентное управление инфраструктурой AmneziaWG.** Разворачивайте контейнеры по SSH, проверяйте узлы, управляйте пользователями, публикуйте подписки для клиентов и сохраняйте контроль над изменениями конфигурации.

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![Node.js](https://img.shields.io/badge/Node.js_%E2%89%A522.13-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://github.com/team-ph4r0s/dementia-panel)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![AmneziaWG](https://img.shields.io/badge/AmneziaWG-88171A?style=flat-square&logo=wireguard&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔌 Безагентное развёртывание**<br>
<sub>Работает с Ubuntu, Debian и AlmaLinux по SSH и умеет подхватывать уже установленные контейнеры.</sub>

**⚡ Горячая синхронизация**<br>
<sub>Применяет изменения через <code>awg syncconf</code> без разрыва активных соединений.</sub>

**📡 Мониторинг и уведомления**<br>
<sub>Проверки узлов, журнал событий и уведомления в Telegram, включая проверки из выбранных регионов.</sub>

</td>
<td width="50%" valign="top">

**🔗 Подписки и мосты**<br>
<sub>Автообновляемые ссылки, QR-коды, ретрансляторы и общий доступ без передачи приватных ключей.</sub>

**🔐 Средства защиты**<br>
<sub>Защита от перебора, коды восстановления TOTP, управление сессиями и шифрованные резервные копии.</sub>

**🧩 HTTPS из коробки**<br>
<sub>Установка одной командой с Let's Encrypt, собственным или самоподписанным сертификатом.</sub>

</td>
</tr>
</table>

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/dementia-panel) &nbsp;·&nbsp;
[Резервные копии](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/backups.md) &nbsp;·&nbsp;
[Перенос](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/migration.md) &nbsp;·&nbsp;
[Проверки](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/probes.md) &nbsp;·&nbsp;
[Мосты](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/bridges.md) &nbsp;·&nbsp;
[Changelog](https://github.com/team-ph4r0s/dementia-panel/blob/main/CHANGELOG.md)

</div>

<br>

### 🏢 [land.inc](https://github.com/team-ph4r0s/land.inc)

**Живой офис для локальной работы ИИ-агентов.** land.inc превращает сессии Claude Code, Codex и Antigravity в жителей изометрического 2.5D-офиса: можно видеть текущую работу, просматривать недавнюю активность и координировать задачи без отправки журналов сессий в отдельное облако land.inc.

- 👀 **Наблюдение за локальной работой** — сессии сгруппированы по проектам и отображаются в зонах офиса.
- 🧭 **Постановка задач** — на доске можно выбрать папку, провайдера, модель, уровень рассуждений и режим доступа.
- 🤝 **Командная работа** — планировщик, исполнитель, проверяющие и доработка собраны в одну историю.
- 🧪 **Безопасная демонстрация** — фейковые агенты позволяют показать офис без вызовов моделей.
- 🏠 **Локальная работа** — демон слушает loopback и читает существующие локальные журналы и CLI провайдеров.

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/team-ph4r0s/land.inc)
[![Node.js](https://img.shields.io/badge/Node.js_24%2B-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://github.com/team-ph4r0s/land.inc)
[![PixiJS](https://img.shields.io/badge/PixiJS-E72264?style=flat-square&logo=pixijs&logoColor=white)](https://github.com/team-ph4r0s/land.inc)

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/land.inc) &nbsp;·&nbsp;
[Быстрый старт](https://github.com/team-ph4r0s/land.inc#быстрый-старт) &nbsp;·&nbsp;
[Changelog](https://github.com/team-ph4r0s/land.inc/blob/main/CHANGELOG.md) &nbsp;·&nbsp;
[Последний релиз](https://github.com/team-ph4r0s/land.inc/releases/latest)

</div>

<br>

### 🎓 [MPEI.Hub](https://github.com/team-ph4r0s/mpei-next)

**Быстрый помощник студента с приоритетом приватности для Национального исследовательского университета «МЭИ».** MPEI.Hub объединяет офлайн-расписание, доступ к БАРС с 2FA, карту Лефортовского кампуса, заметки, напоминания и аккуратный интерфейс на Compose, а также развивающуюся iOS/Kotlin Multiplatform-часть.

- 📅 **Расписание без прокси** — получает данные из официального API МЭИ, кэширует их локально и сообщает об изменениях.
- 🔐 **БАРС с 2FA** — поддерживает TOTP-аутентификаторы и доступные сценарии через мессенджеры и электронную почту.
- 🗺️ **Офлайн-карта кампуса** — навигация на базе OpenStreetMap без Google Play Services и API-ключей.
- 🎨 **Адаптивный интерфейс** — Material 3, OLED-чёрный, виджеты, планшеты и складные устройства.
- 📵 **Политика нулевого трекинга** — без Firebase, аналитики, рекламных SDK и телеметрии сбоев.

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://github.com/team-ph4r0s/mpei-next)
[![Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://github.com/team-ph4r0s/mpei-next)
[![Android](https://img.shields.io/badge/Android-34A853?style=flat-square&logo=android&logoColor=white)](https://github.com/team-ph4r0s/mpei-next)
[![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/team-ph4r0s/mpei-next/blob/main/docs/IOS.md)

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/mpei-next) &nbsp;·&nbsp;
[**📥 Скачать APK**](https://github.com/team-ph4r0s/mpei-next/releases/latest) &nbsp;·&nbsp;
[English README](https://github.com/team-ph4r0s/mpei-next/blob/main/README.en.md) &nbsp;·&nbsp;
[Документация](https://github.com/team-ph4r0s/mpei-next/tree/main/docs) &nbsp;·&nbsp;
[Релизы](https://github.com/team-ph4r0s/mpei-next/releases)

</div>

## 🤝 Как помочь

| | Действие | Почему это важно |
|:--:|:--|:--|
| ⭐ | **Поставить звезду** | Помогает полезным open-source-проектам находить новых пользователей. |
| 🐛 | **Сообщить о проблеме** | Откройте issue в проекте, которому нужна помощь. |
| 🔧 | **Отправить pull request** | Исправления, документация и новые возможности приветствуются. |
| 🔒 | **Сообщить об уязвимости приватно** | Используйте `SECURITY.md`, если он есть в проекте; не публикуйте чувствительные детали в открытом issue. |

## 💛 Поддержать независимую разработку

Все проекты Pharos бесплатны, имеют открытый исходный код и не содержат рекламы. Если какой-то из них сэкономил вам время или помог сохранить контроль над данными, поддержите дальнейшую разработку, инфраструктуру релизов и работу над безопасностью:

<div align="center">

<a href="https://app.lava.top/pharosteam"><img src="https://img.shields.io/badge/Support%20Team%20Pharos%20on-Lava.top-ffd978?style=for-the-badge&logo=heart&logoColor=14224a" alt="Поддержать команду Pharos на Lava.top"></a>

<br>
<sub>Спасибо, что помогаете сохранять проекты публичными, полезными и независимыми.</sub>

</div>

<br>

<div align="center">

<sub>Arca — AGPL-3.0-only &nbsp;·&nbsp; dementia-panel — MIT &nbsp;·&nbsp; MPEI.Hub — MIT &nbsp;·&nbsp; land.inc — см. репозиторий &nbsp;·&nbsp; Сделано командой <b>Pharos</b></sub>

</div>
