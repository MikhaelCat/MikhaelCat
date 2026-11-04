<div align="center">

# Привет, я Михаил 👋

**Rust Developer • Software Engineer • Security & DevSecOps Enthusiast**

[![Rust](https://img.shields.io/badge/Rust-1.75%2B-dea584?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Linux](https://img.shields.io/badge/Linux-Kernel%20%26%20Drivers-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org/)
[![Security / CTF](https://img.shields.io/badge/Security-CTF%20%7C%20AppSec-e74c3c?style=for-the-badge&logo=target&logoColor=white)](https://github.com/MikhaelCat/THEM-CTF_2026-writeups)
[![GTK / Libadwaita](https://img.shields.io/badge/GUI-GTK4%20%7C%20Libadwaita-3584e4?style=for-the-badge&logo=gnome&logoColor=white)](https://gitlab.gnome.org/GNOME/libadwaita)

*Специализируюсь на системной разработке на **Rust**, прикладной информационной безопасности (CTF, AppSec/DevSecOps), реверс-инжиниринге и создании инженерных симуляторов.*

---

</div>

## 🚀 Избранные проекты

### ⚡ [r-rgb](https://github.com/MikhaelCat/r-rgb)
> **Высокопроизводительный драйвер управления подсветкой клавиатур MSI и нативный Libadwaita GUI на чистом Rust для Linux.**
* **Технологии:** `Rust`, `GTK4`, `Libadwaita`, `Linux hidraw/sysfs ioctl`, `Criterion.rs`, `GitHub Actions CI`
* **Особенности:**
  * Прямая трансляция кадров в микроконтроллер клавиатуры (0% нагрузки на CPU хоста).
  * 50 уникальных аппаратных пресетов анимации, звуковой эквалайзер в реальном времени и термо-реактивный режим.
  * Время компиляции сцены: **~3.6 µs**, сериализация HID-пакетов: **~6.0 µs**.
  * Прошел стресс-тесты на 20 000 непрерывных циклов переключения с AddressSanitizer и `cargo audit` (0 уязвимостей).

---

### 🚩 [THEM-CTF_2026-writeups](https://github.com/MikhaelCat/THEM-CTF_2026-writeups)
> **Коллекция подробных двуязычных (RU / EN) разборов тасков и эксплойтов с соревнований THEM?! CTF 2026.**
* **16 решенных тасков по ключевым дисциплинам ИБ:**
  * **Реверс-инжиниринг:** Деобфускация кастомной виртуальной машины Lua (`last_dance`), реверс нативного Rust-бинарника (`🦀?`), анализ Android APK (`Good9`), распаковка Windows PE и энтропийный анализ (`Entropy Core`).
  * **Pwn & Shellcode:** Написание x86_64 шеллкода в ограниченной памяти (`Baby Shellcode`), эксплуатация ELF-бинарников (`lesgo`).
  * **Web & Сетевые устройства:** Обход аутентификации и инъекции команд в прошивках роутеров (`A Cute Magical Router Gateway` + `Revenge`), веб-эксплуатация уровня 1000 очков (`SEAM`).
  * **Криптография:** Анализ каскадных шифров и коллизий (`Cascadino Chain`, `No 7race`, `Despacito`).

---

### 🧭 [vibecode](https://github.com/MikhaelCat/vibecode)
> **Автономный агентный планировщик поездок по Приморскому краю на Rust.**
* **Технологии:** `Rust`, `Axum`, `SQLite`, `Server-Sent Events (SSE)`, `LLM Agent Cycle`, `Leaflet`
* **Особенности:**
  * Агентный цикл с защитой от промпт-инъекций и оффтоп-запросов (Guardrails).
  * 18 правил пространственной гео-валидации (V01–V18), исключающих ошибки в маршрутах.
  * Параллельный асинхронный сбор данных (OSM, погода, достопримечательности, бронирование).

---

### 🌊 [PPS-submarine](https://github.com/MikhaelCat/PPS-submarine)
> **3D-симулятор автономного необитаемого подводного аппарата (АНПА) с протоколом телеметрии реального времени.**
* **Технологии:** `C#`, `Unity`, `UDP Sockets`, `JSON API`
* **Особенности:** Раздельная сетевая архитектура: управляющий сокет команд (Requests 8080) и высокочастотный стрим телеметрии (Stream 8081).

---

### 🎮 Моддинг и тулинг (Mindustry Ecosystem)
* **[Scheme-Zize](https://github.com/MikhaelCat/Scheme-Zize)** (`Java`) — единый jar-билд для клиента и выделенных серверов (Headless-safe), поддержка схем размером до **512×512**, сетевой протокол администрирования Scheme Net.
* **[unit-table](https://github.com/MikhaelCat/unit-table)** (`JavaScript / Rhino`) — компактный HUD-модуль отслеживания активных боевых единиц на карте в реальном времени.
* **[CanvasForge](https://github.com/MikhaelCat/CanvasForge)** (`JavaScript`) — компилятор графики в игровые схемы полотен с алгоритмами дизеринга Bayer и Floyd–Steinberg.

---

## 🛠️ Стек технологий

* **Языки программирования:** Rust, C#, Java, JavaScript, Python, Bash, Lua
* **Системный уровень & Сети:** Linux API, `sysfs` / `hidraw`, UDP/TCP сокеты, REST, SSE, Axum
* **Информационная безопасность:** Реверс-инжиниринг (Ghidra, IDA Pro, JADX), шеллкодинг, анализ сетевого трафика (Wireshark), Web-security (Burp Suite), криптоанализ
* **Инструменты & DevOps:** Git, GitHub Actions (CI/CD), Docker, Criterion.rs, AddressSanitizer

---

## 🎓 Опыт и образовательные программы

* **Проектные смены и интенсивы Т-Банка / Т-Образование:**
  * Командная разработка прикладных микросервисов и участие в хакатонах.
  * Проектирование надежных бэкендов, интеграция внешних API, реализация guardrails и валидации пользовательского ввода.

---

<div align="center">
<sub>Репозитории и код открыты для код-ревью и предложений. Связаться можно через GitHub Issues или Telegram.</sub>
</div>
