### 101.1 Определение и настройка аппаратной части

16 команд для проверки аппаратной части компьютера в Linux

1. lscpu - Команда lscpu выдает информацию о процессоре и его составляющих. В ней нет каких-либо дополнительных параметров или функциональных возможностей.
2. lshw - список аппаратных устройств. Утилита общего назначения, которая сообщает подробную и краткую информацию о нескольких различных аппаратных устройствах, таких как процессор, память, диск, контроллеры usb, сетевые адаптеры и т.д. Команда lscpu извлекает информацию из различных файлов /proc.
3. hwinfo – информация об аппаратуре компьютера. Утилита hwinfo является еще одной универсальной утилитой зондирования аппаратуры, которая может сообщить подробную и краткую информацию о многих различных аппаратных компонентах, причем может сообщить больше, чем утилита lshw.
4. lspci – список устройств PCI. Команда lspci выдает список всех шин PCI, а также подробную информация об устройствах, которые к ним подключены. Под эту категорию подпадают следующие устройства — адаптер vga, графическая карта, сетевой адаптер, порты usb, контроллеры sata и т.д.
5. lsscsi — список устройств scsi. Выдается список устройств scsi/sata, например, жестких дисков и оптических приводов.
6. lsusb – подробный список шин и устройств usb. Эта команда показывает информацию о контроллерах usb и подробные сведения о подключенных к ним устройствах. По умолчанию выдается краткая информация. Для того, чтобы о каждом порте usb получить подробную информацию, используйте параметр "-v".
7. Inxi - является мега скриптом bash, состоящим из 10000 строк кода, с помощью которого из разных источников и команд системы будет получена подробная информация об аппаратном обеспечении и будет создан отчет в виде, позволяющим его читать пользователям, которые не являются техническими специалистами.
8. lsblk — список блочных устройств. Перечисляется информация о всех блочных устройствах, которыми являются разделы жестких дисков и других устройств хранения данных, например, оптических приводов и флэш-накопителей.
9. df – дисковое пространство файловых систем. Отчеты о различных разделах, об их точках монтирования и о том, сколько в каждом разделе есть свободного места.
10. Pydf – команда df, написанная на языке Python. Улучшенный вариант команды df , написанной на языке python, который выдает информацию в цвете, что выглядит лучше, чем информация, выдаваемая командой df
11. fdisk - Fdisk является утилитой, предназначенной для изменения разделов жестких дисков, и ей также можно пользоваться для получения информации о списке имеющихся разделов.
12. mount - Команда mount используется для монтирования/демонтирования, а также для просмотра смонтированных файловых систем.
13. free – проверка оперативной памяти. С помощью команды free проверьте объем используемой, свободной и общий объема оперативной памяти, имеющейся в системе.
14. dmidecode - Команда dmidecode отличается от всех других команд. Она извлекает информацию об оборудовании, читая для этого данные из структур данных SMBOIS (которые также называются таблицами DMI).
15. Файлы /proc - Во многих виртуальных файлах каталога /proc содержится информация об аппаратном обеспечении и о конфигурациях. Ниже приведены некоторые из них.
16. hdparm - Команда hdparm получает информацию об устройствах sata, например, жестких дисков.