# Задание 01 — Работа с константами

## 📝 Цель задания:
Познакомиться с объектом **Константа** в 1С:Предприятие, научиться создавать и объединять константы, а также настраивать форму для их редактирования.

---

## 📌 Реализовано:
- Созданы следующие константы:
  - `НазваниеОрганизации`
  - `ГенеральныйДиректор`
  - `ИНН`
- Установлены свойства для каждой константы:
  - **Синоним** — для отображения понятного имени пользователю.
  - **Комментарий** — для разработчиков.
  - **Длина** — ограничение на ввод (максимум 1024 символа).
  - **Маска ввода** — позволяет задать формат (например, `999999999999` для ИНН).
- Данные хранятся в базе данных и сохраняются между сеансами.

---

## 📦 Объединение в форму:
Для удобной работы с данными:
- Создана форма констант.
- Включены все три созданные константы.
- Настроен порядок отображения элементов (с помощью стрелок).
- Использованы стандартные команды в свойствах формы, чтобы избежать дублирования интерфейса.

---

## 📂 Расположение конфигурации:
Файлы выгружены в:

