# Bug Reports — Somon.tj

---

## BUG-01
Title: Login button not working

Steps:
1. Open login page
2. Enter valid data
3. Click login

Expected: User logged in  
Actual: Nothing happens

Severity: Critical  
Priority: High

---

## BUG-02
Title: Search shows irrelevant results

Steps:
1. Search “car”
2. View results

Expected: Only car ads  
Actual: unrelated ads appear

Severity: Major  
Priority: Medium

## BUG-UI-01

Заголовок: Цены отображаются не в одном столбце (нарушено выравнивание)

---

### Steps to reproduce:
1. Открыть страницу вакансий
2. Обратить внимание на блок с ценами справа

---

### Expected Result:
Все цены должны быть выровнены по одной вертикальной линии (в одном столбце)

---

### Actual Result:
Цены отображаются на разных уровнях, не выровнены по вертикали



### Severity:
Low

### Priority:
Low

### Screenshot:
bug_report_images/bug_ui_price.png

### Environment:
- OS: Windows 11
- Browser: Chrome Версия: 146.0.7680.178 (официальная сборка) (64 бит)


## BUG-PERF-01

Title: Фильтр по цене применяется с задержкой (7–8 секунд)

---

### Steps to reproduce:
1. Открыть страницу вакансий
2. Установить фильтр по цене (например: до 2000 сомони)
3. Подождать результат

---

### Expected Result:
Результаты должны обновляться сразу или в течение 1–2 секунд

---

### Actual Result:
Фильтр применяется с задержкой примерно 7–8 секунд, сначала ничего не происходит

---

### Severity:
Medium

### Priority:
High

---

### Environment:
- Device: Redmi note 11 pro global 
- OS: Android 11
- Browser: Chrome 145.0.7632.75
- Internet: стабильный

---

### Video:

### Notes:
Возможно проблема связана с медленной обработкой запроса или задержкой на сервере
