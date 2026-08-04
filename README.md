<p align="center">
  <img src="./assets/icon.png" alt="MultiAI Desktop" width="112" height="112">
</p>

<h1 align="center">MultiAI Desktop</h1>

<p align="center">
  AI-редактор и рабочая среда для проектов, моделей, Skills и MCP.<br>
  Один интерфейс для кода, терминала и агентных задач.
</p>

<p align="center">
  <a href="https://github.com/SURVERS/MultiAI-Desktop-Official/releases/latest"><img alt="Скачать для Windows" src="https://img.shields.io/badge/Скачать-Windows%20x64-2563eb?style=for-the-badge&logo=windows11&logoColor=white"></a>
  <a href="https://multiai.store"><img alt="MultiAI" src="https://img.shields.io/badge/multiai.store-Официальный%20сайт-111827?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="Latest release" src="https://img.shields.io/github/v/release/SURVERS/MultiAI-Desktop-Official?display_name=tag&style=flat-square">
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%2F11-0ea5e9?style=flat-square">
  <img alt="Architecture" src="https://img.shields.io/badge/architecture-x64-64748b?style=flat-square">
</p>

---

## Скачать

Откройте [последний релиз](https://github.com/SURVERS/MultiAI-Desktop-Official/releases/latest) и скачайте файл вида:

**MultiAI-Desktop-Setup-VERSION-x64.exe**

Поддерживается Windows 10/11 x64. Установщик позволяет выбрать папку установки и создаёт ярлыки приложения.

> Текущая Windows-сборка ещё не подписана коммерческим сертификатом. Microsoft SmartScreen может показать предупреждение «Неизвестный издатель». Скачивайте приложение только из раздела Releases этого репозитория и при необходимости сверяйте SHA-256 с файлом SHA256SUMS.txt.

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

Для обновления используются файлы latest.yml, установщик и его .blockmap из одного GitHub Release.

## Проверка файла

В PowerShell:

    Get-FileHash .\MultiAI-Desktop-Setup-VERSION-x64.exe -Algorithm SHA256

Сравните результат со строкой для установщика в SHA256SUMS.txt того же релиза.

## Ссылки

- [Официальный сайт](https://multiai.store)
- [Все релизы](https://github.com/SURVERS/MultiAI-Desktop-Official/releases)
- [Сообщить о проблеме](https://github.com/SURVERS/MultiAI-Desktop-Official/issues/new)

## О репозитории

Это официальный публичный репозиторий дистрибуции MultiAI Desktop. Здесь размещаются установщики, метаданные автообновления, контрольные суммы и материалы оформления. Исходный код приложения в этом репозитории не публикуется.

<p align="center">© 2026 MultiAI Desktop</p>
