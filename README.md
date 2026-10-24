# ★ Astra Client — Official Releases

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.16.5-5E9C3A?style=for-the-badge&logo=minecraft" alt="Minecraft 1.16.5">
  <img src="https://img.shields.io/badge/Fabric-Loader-62A47A?style=for-the-badge" alt="Fabric">
  <img src="https://img.shields.io/badge/Release-v1.1.0-6366F1?style=for-the-badge" alt="v1.1.0">
  <img src="https://img.shields.io/badge/Storage-SQLite3-003B57?style=for-the-badge&logo=sqlite" alt="SQLite3">
  <img src="https://img.shields.io/badge/Edition-Esports%20Pro-EF4444?style=for-the-badge" alt="Esports Pro">
</p>

<p align="center">
  Официальный репозиторий релизных сборок, портативного лаунчера и бинарников <b>Astra Client</b> для Minecraft 1.16.5 (Fabric).
</p>

---

## ⚡ Быстрая загрузка (Релиз v1.1.0)

| Файл | Описание | Скачать |
|------|----------|---------|
| `Astra_Launcher_1.1.0.exe` | **Официальный лаунчер Astra v1.1.0** (Portable, Cyberpunk UI, консоль логов) | [**Скачать Лаунчер EXE**](https://github.com/kybex11/astra-releases/releases/download/v1.1.0/Astra_Launcher_1.1.0.exe) |
| `astra-1.1.0.jar` | Основной мод клиента для Fabric 1.16.5 | [**Скачать JAR**](https://github.com/kybex11/astra-releases/releases/download/v1.1.0/astra-1.1.0.jar) *(или из корня репо)* |
| `Install_Astra.bat` | Автоматический установщик в один клик | [**Скачать BAT**](https://raw.githubusercontent.com/kybex11/astra-releases/main/Install_Astra.bat) |
| `SHA256SUMS.txt` | Контрольные суммы файлов релиза | [**Просмотр**](https://raw.githubusercontent.com/kybex11/astra-releases/main/SHA256SUMS.txt) |

---

## 🚀 Установка

### Вариант 1: Через официальный лаунчер Astra
1. Скачайте `Astra_Launcher_1.1.0.exe`.
2. Введите ваш игровой никнейм и выберите объем RAM (4–8 GB).
3. Нажмите зеленую кнопку **«ИГРАТЬ»**.

### Вариант 2: Авто-установка в один клик
1. Скачайте `astra-1.1.0.jar` и `Install_Astra.bat` в одну папку.
2. Запустите двойным кликом `Install_Astra.bat`.
3. Установщик скопирует файл прямо в `%APPDATA%\.minecraft\mods\astra-1.1.0.jar`.
4. Запустите Minecraft с профилем **Fabric Loader 1.16.5**.

---

## 🎮 Горячие клавиши в игре

| Клавиша | Назначение |
|---------|------------|
| **Right Shift** | Открыть нативное меню **Shadcn UI** (слайдеры, бинды, модули, темы, косметика) |
| **Right Alt** | Открыть **Редактор элементов HUD** (перетаскивание, масштаб) |
| **M** | Открыть **Большую карту мира** (зум, перемещение, метки) |
| **B** | Поставить путевую точку (**Waypoint**) на текущих координатах |
| **Браузер** | `http://127.0.0.1:3000` — внешний Web Dashboard с SVG-интерфейсом и REST API |

---

## ✨ Что нового в релизе v1.1.0

- 🧊 **Полный фикс 3D Воксельной Косметики:**
  - Устранена ошибка текстуры плаща на моделях: сгенерирована чистая белая текстура `white.png` со 100% сплошным цветом.
  - **3D Крылья Дракона:** перенесены на лопатки верхней части спины, взмахи и раскрытие крыльев симметрично зеркалируются на оба плеча.
  - **3D Золотой Нимб:** поднят над головой (`Y = -0.70`), плавно покачивается и вращается без артефактов.
  - **3D Рога Демона:** закреплены на висках с рубиновым градиентом и загнутыми назад кончиками.
- 🎨 **Web Dashboard с чистыми SVG-иконками:**
  - Полностью удалены юникод-эмодзи, заменены на четкие векторные SVG-иконки.
  - Каталог из всех 50+ модулей клиента с живыми слайдерами (NumberSetting), переключателями (BooleanSetting), чипами (ModeSetting) и кнопками биндов клавиш.
- 🌐 **Встроенный AstraHttpServer:**
  - Встроенный сервер на порту 3000 с REST API (`/api/modules`, `/api/toggle`, `/api/setting`, `/api/keybind`).
- 🚀 **Astra Launcher 1.1.0:**
  - Новый портативный автономный лаунчер с консолью логов и авто-установкой.

---

## 🔐 Контрольные суммы (SHA-256)

```text
2579dda361ab3179a595fb53fbd2fbcd4922a33ad4c46f76359b44774cc8ac54  astra-1.1.0.jar
4532f2a49e73e82bd9b748e18da13738190c9ce60a49a3227ea6c766e0d9266c  Astra_Launcher_1.1.0.exe
```

---

<p align="center">
  <sub>Astra Client Esports Pro v1.1.0 • Developed by EvelentDev</sub>
</p>
