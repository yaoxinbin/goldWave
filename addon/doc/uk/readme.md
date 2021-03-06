# Goldwave #

* Автори: Joseph Lee, учасники спільноти NVDA.
* Завантажити [стабільну версію][1]
* Завантажити [версію в розробці][2]
* NVDA compatibility: 2017.3 to 2019.1

Цей модуль поліпшує доступність та використання звукового редактора
Goldwave.

## Гарячі клавіші ##

* NVDA+Shift+C: Перемикає промовляння команд під час редагування аудіо.
* Control+Shift+P: Повідомити поточну позицію трека.
* NVDA+Shift+R: Announces remaining time for the currently editing track.
* Control+NVDA+1: Оголошує канал, який ви редагуєте.
* Control+NVDA+2: Оголошує загальну довжину аудіофайла.
* Control+NVDA+3: сумарне оголошення виділеної звукової інформації.
* Control+NVDA+4: Оголошує рівень.

Додаткову інформацію про Goldwave і її клавіатурні команди див. у посібнику
користувача GoldWave.

Примітка: GoldWave 6 вимагає 64-бітну версію Windows 7 або новішу. Для
використання додатка версії 2.0 необхідна NVDA 2014.1 або новіша версія.

## Version 18.07

* Fixed an issue where leading zeroes would not be displayed when trying to
  obtain remaining time for a track.

## Version 17.05

* Added ability to provide debug information when NVDA is running with debug
  logging enabled (NVDA 2017.1 or later).
* Updated translations.

## Version 16.12

* Version scheme is now year.month instead of major.minor.

## Changes for 4.0

* Add-on repository has moved to GitHub (now located at
  https://github.com/josephsl/goldwave).
* Performance improvements when looking up information such as channel name
  and other status information.

## Changes for 3.0

* Added a command to announce remaining time for the current track
  (NvDA+Shift+R).
* Slight improvements when announcing status information such as channel
  information.

## Зміни у версії 2.0

* Підтримка GoldWave 6, включно з 64-бітними версіями програми
  (див. примітку вище).
* Починаючи з версії NVDA 2014.3, довідка додатка доступна у диспетчері
  додатків.
* NVDA тепер повідомляє про вибраний канал при натисканні команди вибору
  каналу, наприклад, Control+Shift+L для лівого каналу.
* Були виправлені різні проблеми з числовими полями редагування, такі як
  поле цензури і виділення часу в діалозі міксування, в тому числі виділення
  тексту, оновлення значень і так далі.
* Налаштування оголошень команд запам'ятовується при перемиканні на інші
  програми.

## Зміни у версії 1.2

* Виправлено помилку, коли NVDA з проблемами промовляла деякі поля
  редагування.
* Нові та оновлені переклади.
* Будь ласка,, зверніть увагу, що у зв'язку з останніми змінами в NVDA,
  виділення аудіо та інші команди стану можуть не працювати належни чином на
  деяких системах.

## Зміни у версії 1.1

* Підтримка оголошення повідомлень за допомогою брайля.
* Сумарне оголошення виділеної звукової інформації доступне мовами,
  відмінними від англійської.
* Додано більше команд оголошень, включно з переміщенням положення мітки і
  операцій видалення/обрізання.
* Виправлено проблему з числовыми полями редагування, наприклад, у різних
  діалогах ефектів, коли не оголошувалося нічого або неправильні назви
  полів.
* Нові та оновлені переклади.

## Зміни у версії 1.0

* Перша версія.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev
