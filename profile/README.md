<div align="center">

<img src="https://raw.githubusercontent.com/team-ph4r0s/.github/main/profile/banner.svg" alt="Team Pharos — открытые инструменты для безопасности и приватности" width="100%">

<br>

**Инструменты, которые светят там, где темно.**<br>
Работают без чужих облаков и телеметрии и остаются полностью под вашим контролем.

<br>

[![Репозитории](https://img.shields.io/badge/Репозитории-team--ph4r0s-14224a?style=for-the-badge&logo=github&logoColor=ffd978)](https://github.com/orgs/team-ph4r0s/repositories)
[![Arca stars](https://img.shields.io/github/stars/team-ph4r0s/arca?style=for-the-badge&label=arca&logo=github&logoColor=14224a&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/arca/stargazers)
[![dementia-panel stars](https://img.shields.io/github/stars/team-ph4r0s/dementia-panel?style=for-the-badge&label=dementia-panel&logo=github&logoColor=14224a&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/dementia-panel/stargazers)

</div>

<br>

## 🏛️ О нас

**Pharos** — это Александрийский маяк, одно из семи чудес света. Мы делаем open-source инструменты в том же духе: надёжные, заметные издалека и нужные тем, кто не готов отдавать свои данные и инфраструктуру в чужие руки.

- 🔓 **Открыто** — весь код под свободными лицензиями, без скрытых зависимостей от чужих облаков.
- 🛡️ **Нулевое доверие** — Arca считает враждебным любой файл, а dementia-panel не ставит на ваши серверы никаких агентов.
- 🏠 **Под вашим контролем** — данные, ключи и конфигурации остаются у вас, телеметрии нет.

<br>

## 🚀 Проекты

| | Проект | Что делает | Платформы | Лицензия |
|:---:|---|---|---|:---:|
| 🛡️ | [**Arca**](https://github.com/team-ph4r0s/arca) | Безопасно открывает документы из ненадёжных источников | Android · iOS | AGPL-3.0 |
| 🧠 | [**dementia-panel**](https://github.com/team-ph4r0s/dementia-panel) | Управляет VPN-серверами AmneziaWG | Linux · Docker | MIT |

<br>

<table>
<tr>
<td colspan="3">

### 🛡️ [Arca](https://github.com/team-ph4r0s/arca)

*Параноидально безопасный просмотрщик документов: **Office, OpenDocument, PDF, RTF, Outlook, Visio, Access** и картинки разбираются в одноразовой Wasm-песочнице без доступа к сети. Arca показывает, что спрятано внутри файла, и делает его стерильную копию.*

[![Rust](https://img.shields.io/badge/Safe_Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://github.com/team-ph4r0s/arca)
[![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)](https://github.com/team-ph4r0s/arca)
[![Android](https://img.shields.io/badge/Android_8–16-34A853?style=flat-square&logo=android&logoColor=white)](https://github.com/team-ph4r0s/arca/blob/main/docs/ANDROID.md)
[![iOS](https://img.shields.io/badge/iOS_16+-000000?style=flat-square&logo=apple&logoColor=white)](https://github.com/team-ph4r0s/arca/blob/main/app/README.md)
[![Swift](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)](https://github.com/team-ph4r0s/arca/blob/main/app/README.md)
[![Release](https://img.shields.io/github/v/release/team-ph4r0s/arca?style=flat-square&label=release&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/arca/releases/latest)

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🦀 100% Safe Rust**<br>
<sub>Парсеры написаны с <code>#![forbid(unsafe_code)]</code> и без библиотек на C/C++: переполнения буфера и use-after-free исключены by design.</sub>

</td>
<td width="33%" valign="top">

**📦 Одноразовая песочница**<br>
<sub>Разбор идёт в <code>wasmi</code> с нулём импортов: ни сети, ни диска, ни часов. После разбора память обнуляется, а песочница уничтожается.</sub>

</td>
<td width="33%" valign="top">

**🔬 «Рентген» макросов**<br>
<sub>VBA, XLM, DDE, OLE и ActiveX, Equation Editor, JavaScript в PDF. Для каждого макроса — вердикт: безобидный, подозрительный или вредоносный.</sub>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🕵️ Утечки и трекеры**<br>
<sub>Внешние шаблоны, трекинг-пиксели, UNC-пути для кражи NTLM-хэшей, схемы вроде <code>ms-msdt:</code>, скрытые листы, белый текст и метаданные автора.</sub>

</td>
<td width="33%" valign="top">

**🧼 Стерильная копия**<br>
<sub>В один тап для OOXML, ODF, Visio и PDF. Картинки перерисовываются в новый PNG без EXIF и GPS, а копия повторно проходит проверку.</sub>

</td>
<td width="33%" valign="top">

**📄 Безопасный просмотр**<br>
<sub>Word, Excel и PowerPoint с диаграммами, ODF, RTF, PDF, письма Outlook, схемы Visio и ER-диаграммы баз Access.</sub>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🧱 Жёсткие квоты**<br>
<sub>Лимиты на вложенность, степень сжатия, память и процессорное время: zip-бомбы и Billion Laughs обрываются, а не вешают устройство.</sub>

</td>
<td width="33%" valign="top">

**🧪 Полигон из 50 атак**<br>
<sub>Follina, CVE-2017-11882, Zip Slip, XXE, утечки NTLM и другие. Образцы генерируются из кода и прогоняются в CI.</sub>

</td>
<td width="33%" valign="top">

**📵 Ни байта в сеть**<br>
<sub>В манифесте нет разрешения <code>INTERNET</code>, нет сторонних SDK и Java-зависимостей. Подписанный воспроизводимый APK.</sub>

</td>
</tr>
</table>

> ✅ **Честные вердикты**: статус `Clean` выдаётся, только если распознан каждый байт документа. Всё неоднозначное получает `Unverified`, а не ложное «безопасно».

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/arca) &nbsp;·&nbsp;
[**📥 Скачать APK**](https://github.com/team-ph4r0s/arca/releases/latest) &nbsp;·&nbsp;
[Архитектура](https://github.com/team-ph4r0s/arca/blob/main/docs/ARCHITECTURE.md) &nbsp;·&nbsp;
[Модель угроз](https://github.com/team-ph4r0s/arca/blob/main/docs/SECURITY_THREAT_MODEL.md) &nbsp;·&nbsp;
[Полигон атак](https://github.com/team-ph4r0s/arca/blob/main/tests/malware-test/README.md) &nbsp;·&nbsp;
[iOS](https://github.com/team-ph4r0s/arca/blob/main/app/README.md) &nbsp;·&nbsp;
[Релизы](https://github.com/team-ph4r0s/arca/tree/main/docs/releases)

</div>

<br>

<table>
<tr>
<td colspan="3">

### 🧠 [dementia-panel](https://github.com/team-ph4r0s/dementia-panel)

*Agentless-ПО для управления серверами **AmneziaWG**: развёртывание в Docker по SSH, мониторинг доступности, учёт пользователей и автообновляемые конфигурации для клиентов.*

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![Node.js](https://img.shields.io/badge/Node.js_≥22.13-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://github.com/team-ph4r0s/dementia-panel)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)
[![WireGuard](https://img.shields.io/badge/AmneziaWG-88171A?style=flat-square&logo=wireguard&logoColor=white)](https://github.com/team-ph4r0s/dementia-panel)

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🔌 Agentless по SSH**<br>
<sub>Разворачивает контейнер AmneziaWG на Ubuntu, Debian и AlmaLinux. Уже установленные контейнеры подхватываются без переустановки.</sub>

</td>
<td width="33%" valign="top">

**🛡️ AmneziaWG 3.x**<br>
<sub>Параметры обфускации со своей рандомизацией для каждого сервера и проверкой протокола. Серверы 1.x обновляются в один клик.</sub>

</td>
<td width="33%" valign="top">

**⚡ Горячая синхронизация**<br>
<sub>Изменения применяются через <code>awg syncconf</code> — без разрыва текущих соединений.</sub>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**🔗 Автообновляемые подписки**<br>
<sub>Ссылки <code>/sub/&lt;token&gt;</code>, QR-коды и готовые конфигурации для клиентов Incy и mihomo.</sub>

</td>
<td width="33%" valign="top">

**🌉 Мосты и партнёры**<br>
<sub>Ретрансляторы с отказоустойчивостью подписок и общий доступ к нодам между двумя панелями — приватные ключи не покидают панель владельца.</sub>

</td>
<td width="33%" valign="top">

**📦 Импорт из AmneziaVPN**<br>
<sub>Перенос серверов по ключам <code>vpn://</code> и переезд самой панели на другой сервер.</sub>

</td>
</tr>
<tr>
<td width="33%" valign="top">

**📡 Мониторинг и уведомления**<br>
<sub>Проверка доступности нод, в том числе из выбранных стран через check-host.net, журнал событий и оповещения в Telegram.</sub>

</td>
<td width="33%" valign="top">

**🔐 Безопасность**<br>
<sub>Защита от перебора, двухфакторная аутентификация TOTP с кодами восстановления и управление сессиями.</sub>

</td>
<td width="33%" valign="top">

**💾 Резервные копии**<br>
<sub>Шифрованные бэкапы в Yandex Disk или Google Drive по расписанию и восстановление из CLI.</sub>

</td>
</tr>
</table>

> 🧩 **Установка одной командой** и **HTTPS из коробки**: Let's Encrypt (Cloudflare DNS-01 или HTTP-01), самоподписанный или собственный сертификат.

<div align="center">

[**📖 Репозиторий**](https://github.com/team-ph4r0s/dementia-panel) &nbsp;·&nbsp;
[Бэкапы](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/backups.md) &nbsp;·&nbsp;
[Перенос](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/migration.md) &nbsp;·&nbsp;
[Проверки доступности](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/probes.md) &nbsp;·&nbsp;
[Мосты](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/bridges.md) &nbsp;·&nbsp;
[Импорт из AmneziaVPN](https://github.com/team-ph4r0s/dementia-panel/blob/main/docs/amnezia-import.md) &nbsp;·&nbsp;
[Changelog](https://github.com/team-ph4r0s/dementia-panel/blob/main/CHANGELOG.md)

</div>

<br>

## 🤝 Как помочь проектам

<table>
<tr>
<td>⭐ <b>Поставьте звезду</b></td>
<td>Это лучший способ сказать, что проект вам полезен, и помочь другим его найти.</td>
</tr>
<tr>
<td>🐛 <b>Сообщите о проблеме</b></td>
<td>Нашли баг или есть идея? Откройте issue в <a href="https://github.com/team-ph4r0s/arca/issues">Arca</a> или <a href="https://github.com/team-ph4r0s/dementia-panel/issues">dementia-panel</a>.</td>
</tr>
<tr>
<td>🔧 <b>Пришлите pull request</b></td>
<td>Pull request'ы приветствуются — от правки опечатки до новой функции.</td>
</tr>
<tr>
<td>🔒 <b>Нашли уязвимость?</b></td>
<td>Не публикуйте её в issue — действуйте по SECURITY.md: <a href="https://github.com/team-ph4r0s/arca/blob/main/SECURITY.md">Arca</a>, <a href="https://github.com/team-ph4r0s/dementia-panel/blob/main/SECURITY.md">dementia-panel</a>.</td>
</tr>
<tr>
<td>💛 <b>Поддержите команду</b></td>
<td>Наши проекты бесплатны, без рекламы и платных функций. Поддержать разработку можно на <a href="https://app.lava.top/pharosteam">Lava.top</a>.</td>
</tr>
</table>

<br>

<div align="center">

<sub>Arca — AGPL-3.0 &nbsp;·&nbsp; dementia-panel — MIT &nbsp;·&nbsp; Сделано командой <b>Pharos</b></sub>

</div>
