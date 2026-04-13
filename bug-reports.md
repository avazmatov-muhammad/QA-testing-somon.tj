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

Title: Фильтр по цене применяется с задержкой

---

### Steps to reproduce:
1. Открыть страницу вакансий IT телеком
2. Установить фильтр по цене (от 8000 сомони)
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
bug_report_video/performance bug.mp4

### Notes:
Возможно проблема связана с медленной обработкой запроса или задержкой на сервере



## BUG-FILT-02

Title: Фильтр по цене от 0 до 0 не влияет на результаты

---

### Steps to reproduce:
1. Открыть страницу вакансий
2. Установить фильтр цены от 0 до 0
3. Применить фильтр

---

### Expected Result:
Отображаются вакансии с ценой 0 или пустой список

---

### Actual Result:
Список вакансий не изменяется

---
### Screenshoot:
bug_report_images/filter zero price bug.jpg

### Severity:
Medium

### Priority:
Medium


## BUG-PERF-02

Title: Кнопка "Позвонить" не реагирует или срабатывает с большой задержкой

---

### Steps to reproduce:
1. Открыть страницу объявления
2. Нажать кнопку "Позвонить"
3. Повторить нажатие 2–3 раза

---

### Expected Result:
Кнопка должна реагировать сразу и выполнять действие (показ номера или вызов)

---

### Actual Result:
- При нажатии ничего не происходит
- Иногда действие выполняется с большой задержкой (~30–45 секунд)
- Повторные нажатия не дают результата

---

### Severity:
High

### Priority:
High

---

### Screenshoot:
bug_report_video/performance bug 2.mp4

### Environment:
- Device: Redmi Note 11 Pro Global
- OS: Android 11
- Browser: Chrome 145.0.7632.75
- Internet: стабильный


## BUG-UI-03

Title: Изображения объявлений обрезаются некорректно в списке

---

### Steps to reproduce:
1. Открыть мобильную версию сайта
2. Перейти в список объявлений
3. Посмотреть на изображения карточек

---

### Expected Result:
Изображения должны отображаться корректно, без обрезания важного контента

---

### Actual Result:
Изображения обрезаются, часть контента (текст/объект) не видна

---

### Severity:
Medium

### Priority:
Medium

---


### Screenshot:
  

### Environment:
- Device: Redmi Note 11 Pro Global
- OS: Android 11
- Browser: Chrome 145.0.7632.75
- Internet: стабильный

