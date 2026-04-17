# 🧪 Test Plan — Somon.tj

---

## 1. Purpose (Цель)

Целью данного тестирования является проверка функциональности, удобства использования и стабильности работы сайта Somon.tj.

---

## 2. Scope (Область тестирования)

### 🔹 In Scope (что тестируем)

**Functional:**
- Поиск объявлений (Search)
- Фильтрация (Filters)
- Просмотр объявления (Ad Page)
- Основные действия пользователя (навигация, открытие страниц)

**UI:**
- Отображение элементов интерфейса
- Выравнивание текста и цен
- Отображение изображений

**Mobile:**
- Адаптивность (Responsive design)
- Корректность отображения на мобильных устройствах

**Performance (базово):**
- Скорость отклика фильтров
- Реакция кнопок (например, "Позвонить")

---

### 🔸 Out of Scope (что НЕ тестируем)

- Backend логика (база данных)
- Безопасность (Security testing)
- Нагрузочное тестирование (Load/Stress)
- Автоматизация (Automation)

---

## 3. Test Types (Виды тестирования)

- Functional Testing  
- UI Testing  
- Negative Testing  
- Exploratory Testing  
- Basic Performance Testing  

---

## 4. Test Design Techniques (Методы тест-дизайна)

- Equivalence Partitioning  
- Boundary Value Analysis (BVA)  
- Negative Testing  

---

## 5. Test Environment (Окружение)

### Desktop:
- OS: Windows 11  
- Browser: Chrome 146 (официальная сборка)  

### Mobile:
- Device: Redmi Note 11 Pro 4G  
- OS: Android 11  
- Browser: Chrome 145  

---

## 6. Entry Criteria (Условия начала тестирования)

- Сайт доступен  
- Основные страницы загружаются  
- Есть доступ к интернету  
- Окружение настроено (браузеры, устройство)  

---

## 7. Exit Criteria (Условия завершения тестирования)

- Выполнены все Test Cases  
- Пройден Checklist  
- Все найденные баги задокументированы  
- Отсутствуют Critical и High баги (или они зафиксированы)  

---

## 8. Deliverables (Артефакты)

- Checklist  
- Test Cases  
- Bug Reports  

---

## 9. Risks (Риски)

- Медленная работа сайта (performance issues)  
- Нестабильное интернет-соединение  
- Ограниченный доступ к некоторым функциям  

---

## 10. Notes (Примечания)

Тестирование проводится как сторонним QA (портфолио-проект), без доступа к внутренней документации и backend части системы.
