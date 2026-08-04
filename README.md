<p align="center">
  <img src="./assets/icon.png" alt="MultiAI Desktop" width="112" height="112">
</p>

<h1 align="center">MultiAI Desktop</h1>

<p align="center">
  AI-редактор и рабочая среда для проектов, моделей, Skills и MCP.<br>
  Один интерфейс для кода, терминала и агентных задач.
</p>

<p align="center">
  <a href="https://github.com/SURVERS/MultiAI-Desktop-Official/releases/latest/download/MultiAI-Desktop-Windows-x64.exe"><img alt="Скачать MultiAI Desktop для Windows x64" src="https://img.shields.io/badge/⬇_СКАЧАТЬ_MultiAI_Desktop-Windows_x64-2563eb?style=for-the-badge&logo=windows11&logoColor=white"></a>
</p>

<p align="center">
  <strong>Обычный компьютер с Windows 10 или 11? Нажимайте синюю кнопку выше.</strong><br>
  Скачивание установщика начнётся сразу — искать файл внутри Releases не нужно.
</p>

<p align="center">
  <a href="https://multiai.store"><img alt="MultiAI" src="https://img.shields.io/badge/multiai.store-Официальный_сайт-111827?style=flat-square"></a>
  <img alt="Latest release" src="https://img.shields.io/github/v/release/SURVERS/MultiAI-Desktop-Official?display_name=tag&style=flat-square">
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows_10%2F11-0ea5e9?style=flat-square">
</p>

---

## Скачать

| Операционная система | Архитектура | Формат | Статус | Загрузка |
|---|:---:|:---:|:---:|:---:|
| **Windows 10/11** | **x64 (64-bit)** | `.exe` | ✅ Поддерживается | **[⬇ Скачать установщик](https://github.com/SURVERS/MultiAI-Desktop-Official/releases/latest/download/MultiAI-Desktop-Windows-x64.exe)** |
| Windows 10/11 | x86 (32-bit) | `.exe` | ❌ Не выпускается | — |
| Linux — универсальный | x64 | `.AppImage` | 🧪 Планируется | Пока нет |
| Ubuntu / Debian / Mint | x64 | `.deb` | 🧪 Планируется | Пока нет |
| Fedora / RHEL / openSUSE | x64 | `.rpm` | 🧪 Планируется | Пока нет |
| Linux | ARM64 | `.AppImage` / `.deb` | ⚪ Не тестировалось | Пока нет |

> **x64** — это практически любой современный компьютер на Intel или AMD. Версия Windows x86/32-bit не выпускается.

### Поддержка Linux

Официальной Linux-сборки пока нет. Интерфейс и часть системных функций уже учитывают Linux, но перед публикацией необходимо собрать и проверить нативные модули, терминал, файловые операции и автообновление на реальных дистрибутивах. До завершения этих проверок Linux не считается поддерживаемой платформой.

## Что умеет MultiAI Desktop

- агентная работа с кодовой базой и контекстом открытого проекта;
- единый каталог AI-моделей через MultiAI;
- несколько чатов и проектных сессий;
- встроенные терминал, редактор и просмотр изменений;
- Skills, MCP-серверы, правила и субагенты;
- изображения и вложения в сообщениях;
- настраиваемые модели рассуждения и режимы доступа.

## Автообновление

Production-сборка использует Releases этого репозитория как публичный update-feed.

- первая проверка запускается вскоре после старта приложения;
- затем IDE проверяет обновления каждый час;
- загрузка выполняется в фоне;
- после загрузки IDE предложит перезапуск;
- автообновление и дифференциальную загрузку можно отключить в настройках.

Для обновления используются файлы `latest.yml`, установщик и его `.blockmap` из одного GitHub Release.

## Проверка файла

В PowerShell:

    Get-FileHash .\MultiAI-Desktop-Windows-x64.exe -Algorithm SHA256

Сравните результат со строкой для установщика в `SHA256SUMS.txt` последнего релиза.

> Текущая Windows-сборка ещё не подписана коммерческим сертификатом. Microsoft SmartScreen может показать предупреждение «Неизвестный издатель». Скачивайте приложение только из этого официального репозитория.

## Ссылки

- [Официальный сайт](https://multiai.store)
- [Все релизы](https://github.com/SURVERS/MultiAI-Desktop-Official/releases)
- [Сообщить о проблеме](https://github.com/SURVERS/MultiAI-Desktop-Official/issues/new)

## О репозитории

Это официальный публичный репозиторий дистрибуции MultiAI Desktop. Здесь размещаются установщики, метаданные автообновления, контрольные суммы и материалы оформления. Исходный код приложения в этом репозитории не публикуется.

<p align="center">© 2026 MultiAI Desktop</p>
