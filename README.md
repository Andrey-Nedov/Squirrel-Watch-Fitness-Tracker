# Умные часы с функциями фитнес-трекера / Smartwatch with fitness tracker functions
<img src="/imgs/im6.png" width="800"/>

*01.01.2016 - 30.07.2017*  [![Generic badge](https://img.shields.io/badge/Status-Closed-red.svg)](https://shields.io/)<br/>

*Команда/Team*
1. [Андрей Недов](https://github.com/Andrey-Nedov-is-a-human) (16 y.o. hardware, software, manager)
2. Егор Василенко (15 y.o. mobile app programmer)
3. Михаил Онегин (15 y.o. 3D-designer)
<br/>

## Цель проекта
Целью проекта было создание простого фитнес-трекера с возможностью синхронизации со смартфоном для вывода на трекер уведомлений.

<img src="/imgs/im7.png" width="700"/>
<img src="/imgs/sm.gif" width="700"/>

## Реализация

### Часы

Устройство базируется на AVR-микроконтроллере Atmega328p в компактном SMD-корпусе. Синхронизацию со смартфоном обеспечивает встренный в часы bluetooth-модуль. Информация о пройденном пути берётся с GPS-модуля смартфона. Так же в устройстве предусмотрен вибромотор для реализации обратной связи.

<img src="/imgs/3d.gif" width="700"/>

В программе SprintLayout была смоделирована разводка основной платы, далее лазерно-утюжным методом переведена на текстолит, который потом поплыл травиться в хлорид-железа.

<img src="/imgs/im8.png" width="600"/>
<img src="/imgs/im9.jpg" width="600"/>
<img src="/imgs/im10.jpg" width="600"/>
<img src="/imgs/im11.jpg" width="600"/>
<img src="/imgs/im12.jpg" width="600"/>

Далее на плату напаивались SMD-компоненты.

<img src="/imgs/im13.jpg" width="600"/>

*Результат*

<img src="/imgs/im14.jpg" width="800"/>

### Приложение

Приложеине написано при помощи фреймворка Cordova с использованием плагинов для работы с Bluetooth- и GPS-модулями, а так же доступа ко входящим звонками и СМС-уведомлениям.
<p>
<img src="/imgs/im1.jpg" width="150"/>
<img src="/imgs/im2.jpg" width="150"/>
<img src="/imgs/im3.jpg" width="150"/>
<img src="/imgs/im4.jpg" width="150"/>
<img src="/imgs/im5.jpg" width="150"/>
</p>

<br/>
<br/>

## Итог

<img src="/imgs/os.gif" width="700"/>

Изготовив минимальный рабочий прототип, команда приняла решение закрыть проект оставив изготовление корпуса.
Команда успешно выступила на научно-практических конференциях и с достоинством отправилась на каникулы.
