<!-- Animated header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=Sergey%20Sula-Petrovskiy&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<!-- Typing effect -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=500&color=764ba2&center=true&vCenter=true&multiline=false&width=700&height=80&lines=Python+Developer+%7C+System+Engineer;Building+offline+AI+systems+on+real+hardware;Whisper+%E2%80%A2+Ollama+%E2%80%A2+Docker+%E2%80%A2+Linux;Performance+over+convenience" />
</p>

---

# Sergey Sula-Petrovskiy

Пишу софт, который работает на реальном железе, а не только в облаке.
Основной фокус — offline AI-системы, обработка речи и инфраструктура вокруг них.

---

## Чем занимаюсь

Строю приложения, где ограничения по памяти, CPU и сети — не баг, а условие задачи.
Работаю на стыке Python-разработки и системного администрирования: от настройки FreePBX до упаковки моделей в Docker.

**Основные направления:**
- **Speech-to-Text** (Whisper, Faster-Whisper) — транскрипция, диаризация, работа с шумом
- **Локальные LLM** (Ollama) — без API-ключей, без интернета, на своём железе
- **Desktop-приложения** (PyQt6) — потому что не всё должно жить в браузере
- **Linux, Docker, сети** — чтобы всё это реально работало в продакшене

---

## Проекты

### 🎙️ AI Voice Chat — офлайн-ассистент с голосовым вводом
Десктопное приложение: запись с микрофона → транскрипция → ответ от локальной LLM.
- Поддержка CPU и GPU пресетов (Faster-Whisper)
- Конфигурация под конкретное железо
- PyQt6 интерфейс, без Electron-оверхеда

`Python · Whisper · Faster-Whisper · Ollama · PyQt6`
➡️ *[ссылка на репозиторий]*

### 📞 Анализ телефонных переговоров
Система для записи и разбора звонков на базе FreePBX.
- Настройка записи вызовов на АТС
- Сравнение STT-движков, выбор оптимального под задачу
- Диаризация спикеров и анализ эмоциональной окраски
- Автоматизация через API

`FreePBX · Python · Audio Processing · NLP`

### 📊 Моделирование транспортных потоков
Математическая модель нерегулируемого перекрёстка.
- Свой OOP-движок симуляции с нуля
- Визуализация в реальном времени
- Алгоритмическая оптимизация пропускной способности

`Python · OOP · Math Modeling`

---

## Стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,linux,docker,postgres,git,github,pytorch,tensorflow&perline=9" />
</p>

| Область | Инструменты |
|---|---|
| **Языки** | Python, SQL, Bash |
| **AI / ML** | Whisper, Faster-Whisper, Ollama, NLP, audio processing |
| **Desktop / Backend** | PyQt6, REST API, Pytest |
| **Инфраструктура** | Linux (Ubuntu, Mint, ALT), Docker, сети, домены, пользователи |

---

## Как я принимаю решения

- **Производительность на первом месте.** Если модель не влезает в 8 ГБ RAM — это проблема архитектуры, а не пользователя.
- **Offline-first.** Зависимость от интернета — это точка отказа. Где можно обойтись без неё — обхожусь.
- **Чистая структура > быстрый хак.** Код, который работает «как-то», ломается в самый неподходящий момент.
- **Инструмент под систему, а не наоборот.** Не натягиваю Kubernetes на задачу, которую решает cron.

---


## Фон

**Образование:** Математика и информатика, КубГУ (выпуск 2025)

**Опыт:** Python Developer / System Engineer — работа с реальной инфраструктурой, продакшен-системами и высоконагруженными средами.

**Языки:** Русский (родной), English (B1)

<!-- Animated footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=100&section=footer&animation=fadeIn" />
</p>
