[![License][license-shield]][license]
[![ESPHome release][esphome-release-shield]][esphome-release]

[license-shield]: https://img.shields.io/static/v1?label=License&message=MIT&color=orange&logo=license
[license]: https://opensource.org/licenses/MIT
[esphome-release-shield]: https://img.shields.io/static/v1?label=ESPHome&message=2026.4&color=green&logo=esphome
[esphome-release]: https://GitHub.com/esphome/esphome/releases/

<div align="center">
  <h1>🔌 EKF Connect RCE — Wi-Fi реле</h1>
  <p><strong>Беспроводные реле для управления нагрузкой</strong></p>
  <br/>
</div>

> ⚠️ **Важно**: Перед прошивкой на ESPHome обязательно посмотрите LOG устройства и сделайте **резервную копию (backup)**.

---

## 📌 Модельный ряд

| Модель | Каналов | Описание | Ссылка |
|:------:|:-------:|----------|:------:|
| **RCE-1-WF** | 1 | Одноканальное Wi-Fi реле | [📁 Перейти](./RCE-1) |
| **RCE-2-WF** | 2 | Двухканальное Wi-Fi реле | [📁 Перейти](./RCE-2) |

---

## ✨ Общие характеристики

| Параметр | Значение |
|----------|----------|
| **Управление** | Wi-Fi (ESPHome) |
| **Напряжение** | 220В (питание от сети) |
| **Монтаж** | DIN-рейка |
| **Прошивка** | ESPHome |

---

## 🖼️ Внешний вид

<div align="center">

| RCE-1-WF | RCE-2-WF |
|:---:|:---:|
| <sub>Одноканальное реле</sub> | <sub>Двухканальное реле</sub> |

</div>

---

## 🔧 Особенности

| № | Особенность |
|:--:|-------------|
| 1 | Компактный корпус для **DIN-рейки** |
| 2 | Управление через **ESPHome** / Home Assistant |
| 3 | Состояние реле сохраняется после перезагрузки |
| 4 | Возможность управления по **MQTT** |
| 5 | **Полная изоляция** силовой и управляющей части |

---

## 📚 Документация

| Модель | Файлы |
|--------|-------|
| RCE-1-WF | [📁 Перейти в папку RCE-1](./RCE-1) |
| RCE-2-WF | [📁 Перейти в папку RCE-2](./RCE-2) |

---

## ⚠️ Важные примечания

| № | Примечание |
|:--:|------------|
| 1 | Монтаж должен выполняться **квалифицированным электриком** |
| 2 | Перед прошивкой **обязательно** отключите питание 220В |
| 3 | Для прошивки используйте **USB-UART** адаптер (3.3В логика) |

---

<div align="center">
  <sub>
    💡 Разработано для ESPHome | 
    📦 Требуется ESPHome 2026.4+
  </sub>
</div>