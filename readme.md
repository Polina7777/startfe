#  Markdown & Git
 Ваша задача - создать своё CV в формате markdown.
 CV или резюме — это документ, который соискатель предоставляет потенциальному работодателю, выставляя свою кандидатуру на открытую вакансию.   

CV создаётся в вашем личном публичном репозитории. Название репозитория cv.  

## Рекомендации EPAM HR department о содержании CV:
 >1. Имя и фамилия
 >2. Контакты для связи
 >3. Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении и способности быстро учиться и узнавать новое)
 >4. Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
 >5. Примеры кода
 >6. Опыт работы. Junior Dev может указать пройденные курсы и тренинги, перечислить учебные проекты, или проекты, выполненные на фрилансе с указанием использованных навыков и ссылками на исходный код.
 >7. Образование (включая курсы, семинары, лекции, онлайн-обучение)
 >8. Английский язык (уровень английского языка, если была языковая практика, расскажите о ней)

#### Обратите внимание.
* CV составляется на английском языке.
* при составлении CV рекомендуется указывать реальные данные
* контакты для связи укажите актуальные: они могут использоваться будущим работодателем, ментором, студентами RS School, проверяющими ваши работы в ходе cross-check
*  в качестве примера кода добавьте собственное решение задачи с сайта[ Codewars](<https://www.codewars.com>), он нужен, чтобы вы научились пользоваться подсветкой кода в markdown
* рекомендуется добавить к CV созданное вами небольшое видеорезюме на английском языке. Продолжительность видео 3-5 минут (±15 секунд). В описание видео на YouTube добавьте его транскрипцию на английском языке. Снять данное видео полезно, так как оно развивает ваши навыки самопрезентации и английского языка. В markdown добавляется ссылка на видео, в html-документ, видео встраивается.



## Порядок работы
 >
  1. В своём GitHub аккаунте создайте публичный репозиторий с названием `cv`
  2. В главной ветке данного репозитория (`main1`) должен находиться только один файл `README.md`
  3. От ветки `main` создайте ветку `gh-pages`. В ветке `gh-pages` создайте файл `cv.md`.
  4. Используя markdown-разметку в файле `cv.md` создайте своё CV.
  5. В файл `README.md"` добавьте ссылку вида `https://github-username.github.io/cv`, в которой вместо `github-username` укажите свой GitHub username. После завершения работы по этой ссылке будет открываться страница CV
  6. После завершения работы откройте Pull Request из ветки `gh-pages` в ветку `main`. **Мержить Pull Request не нужно**

  ## Деплой на GitHub Pages ##
  Если вы верно выполнили все пункты инструкции, ваше CV задеплоилось на GitHub Pages. Такая страница создаётся автоматически при создании ветки `gh-pages`, если в корне этой ветки находится файл в формате .md или .html.

Страница задеплоенного на GitHub Pages приложения доступна по адресу

>`https://github-username.github.io/repository-name`

здесь

* `github-username` - username пользователя GitHub
* `repository-name` - название репозитория

Составить ссылку на GitHub Pages можно вручную, но удобнее и проще её найти настройках репозитория. Для этого откройте настройки репозитория (кнопка с надписью Settings справа вверху) и прокрутите страницу с настройками до блока GitHub Pages). Там вы увидете надпись "Your site is published at ..." и ссылку на GitHub Pages.

Если в ветке `gh-pages` на верхнем уровне находится файл в формате .html, ссылка на GitHub Pages, которая находится в настройках репозитория, откроет html-страницу, созданную на основе этого файла. Если в ветке `gh-pages` на верхнем уровне находится файл в формате .md, к окончанию ссылки, которая находится в настройках репозитория, нужно добавить имя этого файла.

## Требования к коммитам ##

В ветке `gh-pages` должно быть не меньше 3-х коммитов.

*init:* - используется для начала проекта/таска. Примеры:

`init: start youtube-task`
`init: start mentor-dashboard task`

*feat:* - это реализованная новая функциональность из технического задания (добавил поддержку зумирования, добавил footer, добавил карточку продукта). Примеры:

`feat: add basic page layout`
`feat: implement search box` 
`feat: implement request to youtube API`
`feat: implement swipe for horizontal list`
`feat: add additional navigation button`
`feat: add banner`
`feat: add social links`
`feat: add physical security section`
`feat: add real social icons`

*fix:* - исправил ошибку в ранее реализованной функциональности. Примеры:

`fix: implement correct loading data from youtube`
`fix: change layout for video items to fix bugs`
`fix: relayout header for firefox`
`fix: adjust social links for mobile`

*refactor:* - новой функциональности не добавлял / поведения не менял.

 Файлы в другие места положил, удалил, добавил. Изменил форматирование кода (white-space, formatting, missing semi-colons, etc). Улучшил алгоритм, без изменения функциональности. Примеры:

`refactor: change structure of the project`
`refactor: rename vars for better readability`
`refactor: apply eslint`
`refactor: apply prettier`

*docs:* - используется при работе с документацией/readme проекта. Примеры:

`docs: update readme with additional information`
`docs: update description of run() method`