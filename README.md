# Українізатор Age of Wonders: Planetfall

![Статус проекту](https://img.shields.io/badge/Статус-В_розробці-orange?style=flat-square)
[![Платформа LBK](https://img.shields.io/badge/Платформа-LBK_Launcher-blue?style=flat-square)](https://lbklauncher.com)
![GitHub Pull Requests](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![Відкриті Issues](https://img.shields.io/github/issues/EYELESS-UA/Age-of-Wonders-Planetfall-Ukrainian-Localization?style=flat-square)
![Останній коміт](https://img.shields.io/github/last-commit/EYELESS-UA/Age-of-Wonders-Planetfall-Ukrainian-Localization?style=flat-square)

Публічний репозиторій для розробки та координації перекладу гри **Age of Wonders: Planetfall** українською мовою. Наша мета — адаптувати складний науково-фантастичний лор гри, зберігши унікальний стиль кожної з космічних фракцій.

---

## 🚀 Як встановити переклад

### Варіант 1: Через LBK Launcher (Рекомендовано) 🌟
Найпростіший спосіб для гравців. Лаунчер сам оновить файли, коли вийде нова версія перекладу.
1. Завантажте та встановіть лаунчер з офіційного сайту: [LBK Launcher](https://lbklauncher.com).
2. Знайдіть **Age of Wonders: Planetfall** у списку ігор лаунчера.
3. Натисніть кнопку **«Встановити»** навпроти української локалізації.
4. Запускайте гру!

### Варіант 2: Через Steam Workshop (Якщо доступно) 🔵
1. Підпишіться на мод у Майстерні Steam: **[Посилання]()**
2. Запустіть лаунчер Paradox, перейдіть у розділ **Playsets** та переконайтеся, що мод активований.

### Варіант 3: Встановлення вручну (З файлів GitHub) ⚙️
1. Перейдіть у розділ **[Releases](посилання)** та завантажте архів останньої версії.
2. Розпакуйте вміст папки `build` за наступним шляхом:
   * `Documents\Paradox Interactive\Age of Wonders Planetfall\Mods\` (якщо встановлюєте як локальний мод).
3. Активуйте локальний мод у лаунчері гри.

---

## 📂 Структура проекту

* `src/source/` — оригінальні англійські файли гри. **Не редагувати!**
* `src/translation/` — робочі файли, де ведеться переклад та редактура тексту.
* `build/` — готові скомпільовані файли локалізації, призначені для релізу.

---

## 🤝 Як долучитися до розробки

Проект відкритий для нових перекладачів та редакторів.

1. Зробіть **Fork** репозиторію.
2. Редагуйте файли виключно у папці `src/translation/`.
3. Створіть **Pull Request** (PR) із описом ваших правок.

> ⚠️ **Важливо:** Не пошкоджуйте XML-теги та змінні на кшталт `{PlayerName}`, `{HexCost}`, `{StrategicResource}`. Змінюйте лише сам текст.

Якщо ви знайшли помилку чи неточність у грі, створіть **[Issue](https://github.com/EYELESS-UA/Age-of-Wonders-Planetfall-Ukrainian-Localization/issues)** та додайте скріншот з описом проблеми.

---

## 📖 Глосарій (Стартовий шаблон)

Для дотримання єдиного Sci-Fi стилю перекладу ми формуємо внутрішній глосарій. Пропозиції щодо змін приймаються в Issues.

| Англійський термін | Український варіант | Примітка / Контекст |
| :--- | :--- | :--- |
| **Vanguard** | Авангард | Фракція (космодесантники) |
| **Dvar** | Двари | Фракція (космічні гноми) |
| **Kir'Ko** | Кір'ко | Фракція (інсектоїди) |
| **Amazon** | Амазонки | Фракція (біоінженери) |
| **Assembly** | Асамблея | Фракція (кіборги/кібер-некроманти) |
| **Syndicate** | Синдикат | Фракція (торговці/рабовласники) |
| **Cosmite** | Косміт | Рідкісний стратегічний ресурс |
| **Energy** | Енергія | Базовий ресурс (валюта) |

---

## 📈 Статус розробки

* **Інтерфейс, меню та навчання:** ![0%](https://img.shields.io/badge/0%25-red?style=flat-square)
* **Технології та модулі (Tech Tree):** ![0%](https://img.shields.io/badge/0%25-red?style=flat-square)
* **Таємні технології (Secret Tech):** ![0%](https://img.shields.io/badge/0%25-red?style=flat-square)
* **Кампанія та сценарії (Лор):** ![0%](https://img.shields.io/badge/0%25-red?style=flat-square)

---
**Автор проекту:** [EYELESS-UA](https://github.com/EYELESS-UA)  
*Велика подяка спільноті LBK за технічну та інформаційну підтримку українських локалізацій!*