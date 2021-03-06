1. Task: https://rolling-scopes-school.github.io/stage0/#/stage0/tasks/wildlife
2. Screenshot:
   ![изображение](https://user-images.githubusercontent.com/70811102/139672044-e010b8fb-2643-4bab-a281-99f8cfb9a3fd.png)
   ![изображение](https://user-images.githubusercontent.com/70811102/139672097-e09eb3d7-5bc9-4ac9-842c-cc5e6252c80d.png)
   ![изображение](https://user-images.githubusercontent.com/70811102/139672152-961ff5a2-7919-4498-9b39-eb877a06b5a6.png)
3. Deploy: https://hotlovestl.github.io/wildlife/index.html
5. Score: 50 / 50
- Блок Header +10
  - блок Header содержит только логотип и панель навигации. Наличие блоков-обёрток во внимание не принимаем
  - логотип содержит два элемента - svg-иконку и текст. SVG может быть добавлен любым способом. Обращаем внимание на формат, а не на способ добавления  
  - на странице обязательно должен присутствовать один элемент &lt;h1&gt;. Расположите его на свое усмотрение. Не проверяем какой именно элемент указан как &lt;h1&gt;, главное, чтобы он был и был только один
  - панель навигации состоит из четырёх элементов: двух ссылок, иконки поиска и кнопки "Sign in" . Верстается в виде ненумерованного списка: ul > li > a. Если кнопка         "Sign in" верстается не как ссылка, а тегом &lt;button&gt;, это не ошибка
  - все элементы панели навигации должны быть интерактивными
- Блок Survival +10
  - расстояние между буквами заголовка регулируется css-свойством letter-spacing
  - разрывы строк в текстовом блоке регулируются шириной блока без использования тега &lt;br&gt;
  - кнопка Donate интерактивная. Используются указанные в макете стили для различных состояний кнопки
  - у блоков Header и Survival общее фоновое изображение
- Блок Latest articles +10
  - для вёрстки трёх изображений в ряд лучше использовать flexbox или grid. Float использовать можно. &lt;table&gt; - нельзя!
  - надписи поверх изображений можно разместить при помощи абсолютного позиционирования. Менее семантически правильный, но более простой в реализации вариант -               использовать для добавления изображений css-свойство background-image
  - стрелки слайдера интерактивны
- Блок Get notified +10
  - для отправки данных используется тег &lt;form&gt;
  - поле email верстается тегом input с типом text или email (оба варианта допустимы), поле send верстается тегом &lt;input&gt; с типом submit
  - надпись 'email' это placeholder
- Блок Footer +10
  - блок Footer содержит логотип, дополнительную панель навигации и ссылки на социальные сети
  - логотип полностью повторяет логотип блока Header. Речь о визуальном сходстве, а не использовании точно таких же тегов
  - дополнительная панель навигации и ссылки на социальные сети верстаются в виде ненумерованных списков: ul > li > a
  - иконки социальных сетей верстаются с использованием svg-файлов в качестве фоновых изображений
  - все ссылки в футере должны быть интерактивными
