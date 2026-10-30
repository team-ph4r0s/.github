<div align="center">

<img src="https://raw.githubusercontent.com/team-ph4r0s/.github/main/profile/banner.svg" alt="Team Pharos — открытые инструменты для self-hosted инфраструктуры" width="100%">

<br>

**Инструменты, которые светят там, где темно.**<br>
Разворачиваются просто, не требуют агентов и остаются полностью под вашим контролем.

<br>

[![Репозитории](https://img.shields.io/badge/Репозитории-team--ph4r0s-14224a?style=for-the-badge&logo=github&logoColor=ffd978)](https://github.com/orgs/team-ph4r0s/repositories)
[![Stars](https://img.shields.io/github/stars/team-ph4r0s/dementia-panel?style=for-the-badge&logo=github&logoColor=14224a&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/dementia-panel/stargazers)
[![License](https://img.shields.io/github/license/team-ph4r0s/dementia-panel?style=for-the-badge&color=ffd978&labelColor=14224a)](https://github.com/team-ph4r0s/dementia-panel/blob/main/LICENSE)

</div>

<br>

## 🗼 О нас

**Pharos** — это Александрийский маяк, одно из семи чудес света. Мы делаем open-source инструменты в том же духе: надёжные, заметные издалека и нужные тем, кто сам держит свои серверы.

- 🔓 **Открыто** — код под свободной лицензией, без скрытых зависимостей от чужих облаков.
- 🪶 **Без агентов** — управляем по SSH и ничего лишнего не ставим на ваши машины.
- 🏠 **Self-hosted** — данные, ключи и конфигурации остаются у вас.

<br>

## 🚀 Проекты

<table>
<tr>
<td>

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
</table>

<table>
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

## 🤝 Как помочь проекту

| | |
|---|---|
| ⭐ **Поставьте звезду** | Это лучший способ сказать, что проект вам полезен, и помочь другим его найти. |
| 🐛 **Сообщите о проблеме** | Нашли баг или есть идея? Откройте [issue](https://github.com/team-ph4r0s/dementia-panel/issues) и опишите, что произошло. |
| 🔧 **Пришлите pull request** | [Pull request'ы](https://github.com/team-ph4r0s/dementia-panel/pulls) приветствуются — от правки опечатки до новой функции. |
| 🔒 **Нашли уязвимость?** | Действуйте по инструкции в [SECURITY.md](https://github.com/team-ph4r0s/dementia-panel/blob/main/SECURITY.md). |

<br>

<div align="center">

<sub>Распространяется под лицензией MIT &nbsp;·&nbsp; Сделано командой <b>Pharos</b></sub>

</div>
