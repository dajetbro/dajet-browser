# Dajet

**Silent to the network. Loud in style.**

Dajet is a minimal web browser for macOS, built by the [Dajet design studio](https://dajet.ru). Its start screen makes **zero network requests** — widgets run entirely on your Mac's own resources: calendar, reminders, battery, media, time. No config pulled from the cloud, no tips of the day, no telemetry. Open a network monitor and launch Dajet: silence.

> Русская версия ниже · [Скачать (скоро) →](https://dajet.ru/browser)

---

## The idea

Every major browser treats its start page as a storefront — someone else's services, promoted tiles, "helpful" content fetched from the cloud. Dajet's new-tab page is a quiet room: a beautiful theme, local widgets, your links. That's it.

The silence is **verifiable, not promised**. We consider it part of the product, tested in every release checklist.

## What Dajet stands on

- **Minimalism** — in interface, weight and memory. If it can be removed, it is removed.
- **Silence** — zero network requests without an explicit action by you. No telemetry; update checks happen only when you press the button.
- **Themes as art** — every theme is a published design work with a named author. The start screen is the studio's permanent gallery. Themes are plain CSS + wallpapers + a manifest — designers don't write code.

## Local widgets

Clock, calendar, reminders, pomodoro timer, battery & system state, now-playing, notes, quick links — all powered by macOS itself. The category "online widgets" does not exist in Dajet and never will.

## Status

Dajet is in active development. It is built on the engine inside every Mac — **WebKit** — which is why it stays small and opens instantly.

- Current base: fork of [Search](https://github.com/officecommun/search) by Office Commun (MIT)
- Target: macOS 14+
- First public build: watch this repo or [dajet.ru/browser](https://dajet.ru/browser)

## License & credits

Dajet is [MIT-licensed](LICENSE). It stands on the shoulders of [Search](https://github.com/officecommun/search) — thank you, [Office Commun](https://officecommun.com), for a beautiful, quiet browser and a generous license.

---

## Русская версия

**Dajet** — минималистичный браузер для macOS от дизайн-студии [Dajet](https://dajet.ru).

**Молчит в сеть. Говорит стилем.** Стартовый экран не делает ни одного сетевого запроса: виджеты (часы, календарь, напоминания, батарея, «сейчас играет», заметки, быстрые ссылки) работают исключительно на ресурсах вашего Mac. Без телеметрии, без «советов дня», без аккаунтов. Проверьте монитором сети — тишина.

Три кита Dajet:

1. **Минимализм** — в интерфейсе, весе и памяти.
2. **Тишина** — ноль обращений в сеть без вашего действия; обновления — только по кнопке.
3. **Темы как искусство** — каждая тема издаётся с именем автора; стартовый экран — постоянная галерея студии.

Статус: в активной разработке на движке WebKit (форк [Search](https://github.com/officecommun/search), MIT). Первый публичный билд — следите за репозиторием или [dajet.ru/browser](https://dajet.ru/browser).

Лицензия: [MIT](LICENSE).
