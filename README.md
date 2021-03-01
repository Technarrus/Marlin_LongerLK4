# Firmware Marlin for 3D Printer Longer LK4

Конфигурация <a href="https://github.com/MarlinFirmware/Marlin">официальной прошивки  Marlin</a> 2.0.6.1 для 3д принтера Longer LK4

По пути Longer\Marlin2.0.6.1LK4\.pio\build\STM32F103VE_longer есть уже скомпилированная прошивка progect.pin

Если ничего менять не собираетесь, заливайте ее.

## ЧТО ВКЛЮЧЕНО
* Русский язык интерфейса
* Включен LA, возможность изменить ускорения, джерки, скорость и т.п.
* Включение выключение датчика филамента
* Калибровка зазора по Z gо углам
* PID стола и т.д.

## РЕЛИЗЫ
В [релизах](https://github.com/Technarrus/Marlin_LongerLK4/releases/tag/Marlin) архив прошивки с включенным Mesh Bed Leveling если вдруг у кого-то кривой стол, а облегчить работу хочется))

## КАК УСТАНОВИТЬ
* Скопировать progect.pin на SD карту, вставить в слот, включить принтер. Процесс займет около 10 секунд. 
* После прошивки рекомендую сразу вынуть какрту и удалить файл прошивки, иначе прошьется при следующем включении опять.
* Первым делом, перед настройками, сделать инициализацию ипрум.
* Рекомендуется откалибровать PID экструдера, поток, шаги на миллиметр, если используете какие-либо не стандартные шкивы и винт оси Z.

### Связь
Вопросы, обсуждения, предложения через следующие сообщества:
* [Telegram группа](https://t.me/technarr)
* [Группа в VK](https://vk.com/technarrus)
