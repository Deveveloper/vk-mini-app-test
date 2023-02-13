# vk-mini-app-test
Пример vk mini app
## Скачать - https://disk.yandex.ru/d/2R8NFtMZQMquOA

## Что это за репозиторий?
Этот репозиторий является примером приложения VK Mini App с оптимизацией под разные платформы и сменой темы, а также поддержкой системной кнопки "Назад" на Android и свайпов на iOS. Также в *src/panels/features/**Popouts.js*** есть пример реализации модальных окон, карточек, алертов и т.п. 

## Как запустить приложение?
Откройте терминал (консоль) в папке, в которую Вы скопировали репозиторий. Затем введите команду *npm install* и нажмите **Enter**. Когда все зависимости будут установлены (выполнение команды завершится), введите команду *npm start*, подтвердив запуск приложения нажатием **Enter**.

## Можно ли использовать этот репозиторий для создания моего собственного мини-приложения?
Да, конечно.

## Почему в App.js импортирована только одна панель?
В файле App.js только определяются платформа и тема. Всё остальное происходит в файле *src/panels/**Home.js*** *(далее — **Home.js**)*

## Куда добавлять и как импортировать панели?
Вы можете создавать панели в уже созданной папке *src/panels/**features***. Там уже есть несколько панелей для примера. Импортируйте созданные панели в **Home.js** и найдите в нём массив объектов **panels**. Следуя комментариям к коду и уже существующим там панелям, допишите свои. Дальше приложение всё сделает само, Вам не нужно больше ничего редактировать.

## Что за объект bannerInfo?
Эта штука позволяет вывести баннер под меню в десктопной версии. Всё описано в комментариях к коду. Вот пример такого баннера:

![image](https://user-images.githubusercontent.com/93197434/172244248-5845eb86-8eea-4f3a-9868-b29caf9b5296.png)

## Документация и другие материалы
Здесь Вы можете найти полезные сведения, которые Вы можете использовать при разработке сервиса:
- [Документация React JS](https://ru.reactjs.org/docs/getting-started.html)
- [Документация от VK для разработчиков](https://dev.vk.com/guide)
- [Официальное сообщество VK Mini Apps](https://vk.com/vkappsdev)
- [Документация VKUI](https://vkcom.github.io/VKUI/)
- [Иконки VK Icons](https://vkcom.github.io/icons/)

## Наша группа ВКонтакте
- [Наша группа](https://vk.com/devtopstudio)
- [Статья о VK Mini Apps](https://vk.com/@devtopstudio-vk-mini-apps))


