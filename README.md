# ★ Astra Client — Official Releases

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.16.5-5E9C3A?style=for-the-badge&logo=minecraft" alt="Minecraft 1.16.5">
  <img src="https://img.shields.io/badge/Fabric-Loader-62A47A?style=for-the-badge" alt="Fabric">
  <img src="https://img.shields.io/badge/Storage-SQLite3-003B57?style=for-the-badge&logo=sqlite" alt="SQLite3">
  <img src="https://img.shields.io/badge/Release-v1.0.0-6366F1?style=for-the-badge" alt="v1.0.0">
  <img src="https://img.shields.io/badge/Edition-Esports-EF4444?style=for-the-badge" alt="Esports Edition">
</p>

<p align="center">
  Официальный репозиторий релизных сборок и бинарников <b>Astra Client</b> для Minecraft 1.16.5 (Fabric).
</p>

---

## ⚡ Быстрая загрузка

| Файл | Описание | Скачать |
|------|----------|---------|
| `astra-1.0.0.jar` | Основной мод клиента для Fabric 1.16.5 | [**Скачать JAR**](https://github.com/kybex11/astra-releases/releases/download/v1.0.0/astra-1.0.0.jar) *(или из корня репо)* |
| `Install_Astra.bat` | Автоматический установщик в один клик | [**Скачать BAT**](https://raw.githubusercontent.com/kybex11/astra-releases/main/Install_Astra.bat) |
| `SHA256SUMS.txt` | Контрольные суммы файлов релиза | [**Просмотр**](https://raw.githubusercontent.com/kybex11/astra-releases/main/SHA256SUMS.txt) |

---

## 🚀 Установка

### Вариант 1: Быстрая авто-установка (в 1 клик)
1. Скачайте `astra-1.0.0.jar` и `Install_Astra.bat` в одну папку.
2. Запустите двойным кликом `Install_Astra.bat`.
3. Установщик автоматически определит вашу папку Minecraft, создаст `mods/` при необходимости и скопирует мод.
4. Запустите лаунчер с профилем **Fabric 1.16.5**.

### Вариант 2: Ручная установка
1. Установите [Fabric Loader 1.16.5](https://fabricmc.net/use/installer/).
2. Установите [Fabric API 1.16.5](https://modrinth.com/mod/fabric-api) в папку `.minecraft/mods`.
3. Поместите файл `astra-1.0.0.jar` в папку `.minecraft/mods`.
4. Запустите Minecraft!

---

## 🎮 Горячие клавиши по умолчанию

| Клавиша | Назначение |
|---------|------------|
| **Right Shift** | Открыть **Astra Dashboard** (Shadcn-подобный интерфейс с модулями, темами и настройками) |
| **M** | Открыть **Большую карту мира** (зум, перемещение, метки) |
| **B (код 66)** | Быстро поставить путевую точку (**Waypoint**) на текущих координатах |

---

## ✨ Что нового в релизе v1.0.0

- 🗄️ **Локальное хранилище SQLite3:** Вся конфигурация, HUD-позиции, точки (`waypoints`), реплеи и косметика теперь сохраняются в высокопроизводительную локальную базу данных `astra_storage.db` с автоматической миграцией.
- 🏷️ **Пометка "Общий клиент" в табе (как в Lunar):** Клиент автоматически определяет других пользователей Astra на сервере по каналу `astra:presence` и выделяет их стильным акцентным значком `★ ` в Tab-листе.
- 🧚 **3D Визуальная косметика:**
  - 3D Анимированные Крылья за спиной персонажа с динамической физикой взмахов.
  - 3D Парящий светящийся нимб над головой с покачиванием по синусоиде.
  - 3D Рога демона на голове.
  - Поддержка кастомных плащей и скинов.
- 🗺️ **Интерактивная карта мира & Waypoints для MiniMap:**
  - Полноэкранный просмотр рельефа (панорамирование, зум колесиком мыши от 0.4x до 3.0x).
  - Отображение и управление точками прямо на карте и на HUD радаре миникарты.
- ⚡ **Резкий Shift (Old Sneak):** Модуль для мгновенного приседания без сглаживания камеры из современных версий (точь-в-точь как в 1.8).
- 🎯 **Фикс Crosshair Editor:**
  - Исправлено пропадание прицела при масштабе меньше 1.0 (полная поддержка субпиксельного GPU-скейлинга от 0.25x до 3.0x).
  - Палитра расширена до 16 насыщенных цветов в отзывчивой сетке.
- 📦 **Фикс 3D ESP:** Боксы игроков больше не сдвигаются и не улетают при телепортации, езде на транспорте и спавне; исправлено наложение буфера глубины.

---

## 🔐 Контрольные суммы (SHA-256)

```text
2776d9eec812f070cf2cc8fd607178ee34f26e65c9014deb8e1daf78e12ccb50  astra-1.0.0.jar
```

---

<p align="center">
  <sub>Astra Client Esports Edition • Developed by EvelentDev</sub>
</p>
