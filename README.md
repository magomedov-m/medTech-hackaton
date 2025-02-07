# Автоматизация адресного хранения на складе медицинского оборудования

## Описание проекта

Этот проект представляет собой систему автоматизации адресного хранения на складе медицинского оборудования для ООО «МЕДТЕХНИКА». Цель проекта — улучшение эффективности работы склада за счёт сокращения времени на поиск товаров, снижения количества ошибок и повышения производительности сотрудников.

---

## Функциональность

1. **Мобильное приложение для складских сотрудников**
   — Создано для удобной навигации и учёта позиций на складе.

2. **Веб-панель для руководителей**
   — Обеспечивает возможность аналитики и управления складскими процессами.

3. **Интеграция с ERP-системой 1С**
   — Автоматическое обновление данных о товарах, их перемещении и учёте.

4. **Аналитика и отчётность**
   — Возможность создавать отчёты для анализа эффективности складских операций.

5. **Защита данных**
   — Реализовано разграничение доступа для различных ролей пользователей.

---

## Ключевые выгоды

- Снижение времени на поиск и обработку заказов.
- Сокращение количества ошибок ручного учёта.
- Интеграция с текущей ERP-системой без необходимости замены существующего подхода.
- Гибкость и масштабируемость решения для складов разных размеров.

---

## Структура проекта

- **/mobile-app** — Исходный код мобильного приложения.
- **/web-panel** — Веб-панель для руководителей.
- **/integration** — Модуль для интеграции с ERP системой. (На данный момент не реализован. Планируется в ближайшее время).
- **/analytics** — Инструменты для анализа и отчётов.

---

## Графики статистика отправленных и полученных товаров.

<p align="center">
  <img src="https://github.com/raxa-akh/hackaton/blob/main/src/assets/Аналитика1.png" alt="Аналитика отправленных товаров" width="45%" style="margin-right: 10px;">
  <img src="https://github.com/raxa-akh/hackaton/blob/main/src/assets/Аналитика2.png" alt="Аналитика полученных товаров" width="45%">
</p>

---

## Как начать работу

1. Клонируйте репозиторий:  
   ```bash
   git clone https://github.com/ссылка на этот репозиторий
   ```

2. Установите зависимости для мобильного приложения:  
   ```bash
   cd hackaton
   npm install
   ```

3. Запустите веб-приложение:  
   ```bash
   npm start
   ```

4. Установите зависимости для веб-панели:  
   ```bash
   cd ../web-panel
   npm install
   ```

5. Запустите веб-панель:  
   ```bash
   npm start
   ```

6. Настройте интеграцию с ERP-системой, следуя инструкциям в **/integration/README.md**.

--- На данный момент отсутствует

## Поддержка и обратная связь

Если у вас есть вопросы или предложения, пожалуйста, свяжитесь с нами по адресу: magomedovworkdev@gmail.com.

