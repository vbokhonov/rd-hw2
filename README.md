How to launch project:
1) download project
2) open InstaApp.xcodeproj file in Xcode
3) switch iPhone simulator in dark appearance mode: Settings -> Developer -> Dark Appearance


DONE Небходимо создать iOS приложение, состоящее из 1 экрана -- экран логина (login), взятый из реально приложения Instagram.

DONE - приложение должно собираться и запускаться у меня через Xcode без каких-либо ошибок компиляции (warnings допускаются).

DONE - Приложение должны запускаться только под iPhone/iPod.

DONE - на главной странице репозитория (или в корневой папке проекта) должно быть описание того, как мне запустить проект (даже если это одна строка текста, где говориться "скачать репозиторий и открыть .xcodeproj файл).

DONE - приложение должно иметь такой дизайн, как изображено на прилагаемом скриншоте. Важно: доскональная точность мне не нужно, если вы не знаете, сколько пикселей отступ между надписью Instgram и полем для ввода username, подберите "на глаз", чтобы визуально было похоже на то, как на скриншоте.

DONE - шрифты и картинки можно найти в интернете (пример: картинки искать на https://icons8.com). Идеальную точность соблюдать не надо, но визуально выбранные ваши иконки/шрифты должны быть похожи на те, что на скриншоте.

DONE - все кнопки, что вы видите на экране ("forgot password", "log in", "Continue as Nikita Khomitsevych", "sign up") должны визуально нажиматься. Никаких реальных действий (по типу открытия нового экрана для регистрации, или входа через facebook под моим аккаунтом) делать **не нужно**! Единственное действие, которое должно выполняться при нажатии на любую из вышеперечисленных кнопок -- вывод текста в консоль Xcode (использовать ф-ию `print`).

DONE - оба текстовых поля ввода (username, password) должны иметь text placeholder (если пользователь ничего не ввёл в какое-либо поле). Текст плейсхолдеров: "Username" и "Password" соответственно.

DONE - кнопка "closed eye" должна выполнять функцию показа/сокрытия введенного пароля в текстовое поле. 

DONE - По-умолчанию (при запуске приложения) кнопка показывает изображение закрытого клаза,

1/2 DONE - после нажатия на кнопку -- картинка меняется на "opened eye", и весь текст пароля должен стать виден на экране

TBD - Когда появляется клавиатура на экране (когда юзер нажал на поле ввода текста), кнопка Return клавиатуры должна скрывать клавиатуру.

TBD - Когда клавиатура видна на экране, если пользователь нажал в любую точку экрана, кроме клавиатуры -- клавиатура также должна скрыться (как при нажатии на кнопку Return).

DONE - приложение должно работать только в Portrait режиме. Переворачивание телефона не должно менять ориентацию интерфейса приложения.

TBD - нижняя часть экрана должна быть статической и всегда видна внизу (iOS разработке называется `footer`). Если вы сделали так, что на каком-либо маленьком девайсе у вас скрывается footer -- нужно сделать так, что бы он всегда показывался, даже если контент на экране не влезает. К примеру, кнопка "Continue as Nikita Khomitsevyc" частично прячется под экраном.

Другое:
Появился вагон ворнингов в консоли (проблема с констрейнтами логотипа)
