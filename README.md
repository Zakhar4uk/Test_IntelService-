# Test_IntelService

## Задание №1

Проведите тестирование формы обратной связи и напишите чек-лист. В случае обнаружения ошибок и дефектов оформите их в виде баг-репорта.

### 1. Поля ввода:

- **ФИО:**
  - Проверить, что поле принимает только буквы и пробелы.
  - Проверить, что поле не допускает ввод цифр или специальных символов.
  - Проверить работу валидации на обязательность заполнения (оставить поле пустым и отправить форму).
  
- **Компания:**
  - Проверить, что поле допускает буквы, цифры и символы, такие как "-", "&" и пробелы.
  - Проверить возможность оставлять поле пустым (необязательное поле).

- **E-mail:**
  - Проверить валидацию на корректный формат email-адреса.
  - Проверить, что форма не отправляется с некорректным email (например, без символа "@").

- **Категория обращения:**
  - Проверить, что список категорий раскрывается корректно.
  - Проверить возможность выбора категории из выпадающего списка.
  - Проверить обязательность выбора (отправить форму без выбора категории).

- **Файлы:**
  - Проверить загрузку файла (форматы: jpg, png, pdf и т.д.).
  - Проверить максимальный размер загружаемого файла.
  - Проверить валидацию при загрузке неподдерживаемых форматов файлов.

- **Текст обращения:**
  - Проверить возможность ввода большого объема текста.
  - Проверить ограничение на максимальное количество символов (если есть).

### 2. Функциональные кнопки:

- **Очистить:**
  - Проверить, что все поля формы очищаются после нажатия на кнопку «Очистить».

- **Отправить:**
  - Проверить, что форма отправляется при корректном заполнении всех обязательных полей.
  - Проверить, что форма не отправляется при некорректно заполненных или пустых обязательных полях.
  - Проверить появление сообщения об успешной отправке или ошибке.

### 3. Уведомления и сообщения:

- Проверить, что при некорректном заполнении выводятся соответствующие уведомления об ошибках под полями.
- Проверить, что после успешной отправки выводится сообщение об успешной отправке.

### 4. Кроссбраузерное тестирование:

- Проверить работоспособность формы в разных браузерах (Chrome, Firefox, Safari, Edge).
- Проверить отображение и функциональность на мобильных устройствах (адаптивность).

### 5. Тестирование с разными наборами данных:

- Проверить отправку формы с минимальными, максимальными и средними объемами данных.
- Проверить поведение формы при вводе специальных символов, пробелов и других необычных данных.
