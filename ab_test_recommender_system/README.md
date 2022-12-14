# Проект:
# Анализ результатов А/В теста.

## Описание проекта:

### Назначение теста:

Тестирование изменений, связанных с внедрением улучшенной рекомендательной системы.

Ожидаемый эффект от изменений: за 14 дней с момента регистрации пользователи покажут улучшение целевых метрик не менее чем на 10%.

### Задача:

Проанализировать и оценить результаты А/В теста, а также корректность его проведения.

### Данные для исследования:

- данные пользователей, зарегистрировавшихся в период проведения теста (идентефикатор, дата регистрации, регион и устройство с которого регистрировался пользователь);
- данные пользователей, участинков теста (идентификатор пользователя, название теста, группа пользователя);
- данные о событиях пользователей (идентификатор пользователя, дата и время события, тип события, дополнительные данные, стоимотсь покупки);
- календарь маркетинговых событий.

### Используемые библиотеки:
- pandas,
- scipy,
- numpy,
- matplotlib.

### Результат.
Были выявлены критические ошибки при проведении А/В теста. Это позволило избежать неверных решений по внедрению изменений в системе. Даны рекомендации по дальнейшему проведению подобных экспериментов.
