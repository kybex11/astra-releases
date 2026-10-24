# ★ Astra Client — Official Releases

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.16.5-5E9C3A?style=for-the-badge&logo=minecraft" alt="Minecraft 1.16.5">
  <img src="https://img.shields.io/badge/Fabric-Loader-62A47A?style=for-the-badge" alt="Fabric">
  <img src="https://img.shields.io/badge/Engine-Ultralight%20CEF-A855F7?style=for-the-badge" alt="Ultralight">
  <img src="https://img.shields.io/badge/Storage-SQLite3-003B57?style=for-the-badge&logo=sqlite" alt="SQLite3">
  <img src="https://img.shields.io/badge/Release-v1.0.0-6366F1?style=for-the-badge" alt="v1.0.0">
  <img src="https://img.shields.io/badge/Edition-Esports%20Pro-EF4444?style=for-the-badge" alt="Esports Pro">
</p>

<p align="center">
  Официальный репозиторий релизных сборок, лаунчера и бинарников <b>Astra Client</b> для Minecraft 1.16.5 (Fabric).
</p>

---

## ⚡ Быстрая загрузка

| Файл | Описание | Скачать |
|------|----------|---------|
| `Astra_Launcher_1.0.0.exe` | **Официальный лаунчер Astra** (Portable, современный GUI, авто-настройка) | [**Скачать Лаунчер EXE**](https://github.com/kybex11/astra-releases/releases/download/v1.0.0/Astra_Launcher_1.0.0.exe) |
| `astra-1.0.0.jar` | Основной мод клиента для Fabric 1.16.5 | [**Скачать JAR**](https://github.com/kybex11/astra-releases/releases/download/v1.0.0/astra-1.0.0.jar) *(или из корня репо)* |
| `Install_Astra.bat` | Автоматический установщик в один клик | [**Скачать BAT**](https://raw.githubusercontent.com/kybex11/astra-releases/main/Install_Astra.bat) |
| `SHA256SUMS.txt` | Контрольные суммы файлов релиза | [**Просмотр**](https://raw.githubusercontent.com/kybex11/astra-releases/main/SHA256SUMS.txt) |

---

## 🚀 Установка

### Вариант 1: Через Astra Launcher (Рекомендуется)
1. Скачайте `Astra_Launcher_1.0.0.exe`.
2. Запустите лаунчер, введите игровой никнейм и выберите объем RAM (4–8 GB).
3. Нажмите зеленую кнопку **«ИГРАТЬ»**.

### Вариант 2: Быстрая авто-установка мода (в 1 клик)
1. Скачайте `astra-1.0.0.jar` и `Install_Astra.bat` в одну папку.
2. Запустите двойным кликом `Install_Astra.bat`.
3. Установщик автоматически определит вашу папку Minecraft, создаст `mods/` при необходимости и скопирует мод.
4. Запустите любой лаунчер с профилем **Fabric 1.16.5**.

### Вариант 3: Ручная установка
1. Установите [Fabric Loader 1.16.5](https://fabricmc.net/use/installer/).
2. Поместите файл `astra-1.0.0.jar` в папку `.minecraft/mods`.
3. Запустите Minecraft!

---

## 🎮 Горячие клавиши по умолчанию

| Клавиша | Назначение |
|---------|------------|
| **Right Shift** | Открыть **Astra Web GUI (Ultralight CEF)** меню настроек и модулей |
| **Right Alt** | Открыть **Редактор элементов HUD** (перетаскивание, масштаб) |
| **M** | Открыть **Большую карту мира** (зум, перемещение, метки) |
| **B** | Быстро поставить путевую точку (**Waypoint**) на текущих координатах |

---

## ✨ Что нового в релизе v1.0.0

- 🧊 **Объемная 3D воксельная косметика (MC-стиль):**
  - Полноценные 3D кубические модели с физическим направленным затенением граней (1.0 сверху, 0.55 снизу, 0.8/0.65 по бокам).
  - 3D Воксельные Крылья Дракона (Dragon Wings) с многосегментной структурой костей, когтей и динамическими взмахами.
  - 3D Воксельный Парящий Золотой Нимб (Halo) из 8 сегментов с плавным синусоидальным покачиванием.
  - 3D Воксельные Рога Демона (Demon Horns) с рубиновым градиентом.
- 🌐 **Web GUI на Ultralight (CEF):**
  - Высокопроизводительный современный интерфейс с плавной анимацией и поддержкой веб-стандартов.
  - Открытие по нажатию **Правого Shift**.
- 🗄️ **Локальное хранилище SQLite3:**
  - Конфигурации, HUD-позиции, метки Waypoints и косметика надежно сохраняются в `astra_storage.db`.
- 🏷️ **Пометка "Общий клиент" в табе (как в Lunar):**
  - Автоматическое определение игроков с клиентом Astra по внутреннему каналу `astra:presence` со стильной фиолетовой звездой `★ ` в Tab-листе.
- ⚡ **Резкий Shift (Instant Sneak):**
  - Возможность мгновенного приседания без анимационной задержки камеры.
- 🎯 **Умный AimAssist & Bow Prediction:**
  - Быстрая плавная доводка до цели и расчет траектории полета стрелы из лука с учетом гравитации.
- 🗺️ **Топографическая миникарта & Большая карта:**
  - Корректная высота поверхности без прыжков слоя при прыжках персонажа.
- 💫 **JumpCircles & TargetESP:**
  - Расходящиеся кольца на земле при прыжке и световой ореол вокруг атакуемой цели.

---

## 🔐 Контрольные суммы (SHA-256)

```text
13ba23c119f1e71ba3823351df88f935600b7f445c3e44acc4c277cef68d34ca  astra-1.0.0.jar
5a1001c710972e6379b0f86a3247551def148c8c7ebdc398a6defdbe03e2d7b7  Astra_Launcher_1.0.0.exe
```

---

<p align="center">
  <sub>Astra Client Esports Pro • Developed by EvelentDev</sub>
</p>
