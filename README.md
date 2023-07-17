# План автоматизации тестирования возможности записаться на обучение профессии "Тестировщик ПО" на веб-сайте Нетологии

## Перечень автоматизируемых сценариев:
1. Переход к форме записи через пролистывание всей страницы профессии.
2. Переход к форме записи через кнопку "Записаться" на странице профессии.
3. Переход к форме записи через меню "Каталог курсов".
4. Переход к форме записи через меню "Направления обучения".
5. Заполнение формы записи с действительными данными.
6. Заполнение формы записи с недопустимыми данными (например, пустые поля или некорректные значения).

## Перечень используемых инструментов:
- #### Инструмент автоматизации: Selenide.
  Это широко используемый инструмент для автоматизации тестирования веб-приложений, который поддерживает различные языки программирования и браузеры. Он обладает гибкостью, позволяет воспроизводить действия пользователя и проверять элементы на странице.
- #### Язык программирования: Java.
  Java широко используется в автоматизации тестирования и имеет обширные возможности для работы с Selenide.
- #### Интегрированная среда разработки (IDE): IntelliJ IDEA.
  IntelliJ IDEA является мощной и удобной IDE для разработки на Java. Она предоставляет широкие возможности для написания, отладки и управления проектами.
  
## Перечень необходимых разрешений, данных и доступов:
- Разрешение на доступ к веб-сайту Нетологии и его страницам.
- Доступ к исходному коду веб-страниц, чтобы идентифицировать элементы и их атрибуты для взаимодействия через Selenide.
- Доступ к документации Selenide и его API.
  
## Перечень и описание возможных рисков при автоматизации:
- #### Изменения на веб-сайте:
  Если веб-сайт Нетологии будет изменен, то автоматизированные сценарии могут стать неработоспособными и потребуют обновления.
- #### Непредсказуемое поведение:
  Веб-сайты могут иметь различное поведение в зависимости от загрузки, настроек браузера, куки и других факторов. Необходимо учесть такие вариации во время разработки автоматизированных сценариев.
- #### Зависимость от сторонних ресурсов:
  Если автоматизированные сценарии требуют взаимодействия с другими системами или API, то отказ или изменение этих ресурсов может повлиять на надежность автоматизации.
  
## Перечень необходимых специалистов для автоматизации:
- QA-инженер с опытом автоматизации тестирования веб-приложений.
  Он должен быть знаком с Selenide, Java и фреймворком тестирования, таким как TestNG или JUnit.
- Веб-разработчик или доступ к команде разработчиков для получения помощи при идентификации элементов на странице или внесения изменений в код, если это необходимо для автоматизации.

## Интервальная оценка с учётом рисков в часах:
- Сценарий 1: 3 часа
- Сценарий 2: 3 часа
- Сценарий 3: 5 часов
- Сценарий 4: 5 часов
- Сценарий 5: 2 часа
- Сценарий 6: 2 часа

Общая: 20 часов
