# 🧱 Finora Commit Convention

Единый стиль коммитов для всех проектов экосистемы **Finora Labs**.  
Формат основан на [Conventional Commits](https://www.conventionalcommits.org/), с адаптацией под архитектуру Finora.

---

## 🔹 Формат коммита

(): 

- type — тип изменений (см. таблицу ниже)  
-ENTION.md, — область (например: файла Отлично ⚡
ВоОтлично Отлично ⚡
 `config`)  
-шаблон файла — краткое описание изменений (до 80 символов)

---

## 🔸 Основные типы

| Тип | Назначение |
|------|-------------|
| (наприм| Новая функциональность |
|OMMIT_C| Исправление ошибок |
|ла COMMI| Обновление документации |
|MMIT_CONV| Визуальные изменения, не влияющие на логику |
|который нужн| Рефакторинг кода без добавления нового функционала |
| нужно д| Добавление или изменение тестов |
|VENTION.m| Технические задачи, не влияющие на поведение приложения |
|о добави| Оптимизация производительности |
|NVENTI| Изменения в CI/CD |
|йла COMMI| Сборка, зависимости и пакеты |

---

## 💡 Примеры

feat(api): add endpoint for portfolio listing
fix(db): correct initialization of H2 schema
docs(readme): update project setup instructions
style(frontend): tweak Finora color palette and typography
refactor(api): simplify PortfolioService structure
chore(config): update Spring Boot dependencies

---

## 🧭 Рекомендации

- ПишиLabs**.  
Формат основан  отражающие цель изменения.  
- ИспользуйION.md, который нужно если проект публичный.  
- Каждый коммит должен решатьй нужно добавить в папку
📁 .gi  
- Избегай фраз вроде “update”, “fix some stuff”, “changes”.

---

📘 Пример хорошей истории коммитов:

feat(api): initialize Finora API with H2 and Portfolio entity
fix(api): correct JSON encoding for Cyrillic text
docs(readme): add logo and basic setup steps
style(frontend): add base layout and color scheme

---

✨ *Following this convention keeps Finora projects clean, scalable, and professional.*
