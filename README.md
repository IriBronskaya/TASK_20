# Практика к Модуль 20. Стандарты написания кода и общие подходы
Необходимо взять уже сверстанный сайт (из предыдущего задания)

# https://github.com/IriBronskaya/TASK_18

И доработать его, используя принципы и стандарты.


 ## Список недоработок
 
 1. Применен принцип YAGNI — You ain’t gonna need it (Вам это не понадобится)
 Как пример: "Заказчик посчитал что наиболее актуальнa мобильная версия сайта, поэтому были сделаны
 изменения в меню." Доработана меню-мобильная версия и убрано footer меню.

 2. Применен принцип DRY (не повторяйте себя) к CSS-коду, определены общие стили и объединены  в одно
 
 3. Применен принцип KISS — Keep it simple and straightforward (Простота кода превыше всего). 
 Удалены ненужные атрибуты и классы. Упрощен код в contacts-info.
 
 4. Применен принцип SOLID. Добавлен fail CSS stylemedia; куда перенесены все стили по @media, такое разделение ответственности,
 делает код более понятным и независимым от других файлов.
 
 5. Проверена семантикa и валидность верстки сайта.
 
 6. Применен БЭМ, к разделу photo presentation, исправленны стиле в соответствии с изменениями.

  Beautify не использовала потому что в VS Code написано, что "Это нерекомендуемое приложение, потому что оно больше не поддерживается."
  JSLint и JSHint — линтеры для JavaScript, такого файла нет в наличии проекта.
 
