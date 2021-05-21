# Readme


  Четвертое задание.
Стенд для домашнего занятия "ZFS"

## Описание

Техническое задание на освоение работы c файловой системой Zettabyte (ZFS). 


## Цель

  - Научиться применять команды для разметки дисков и создания пулов.

  - Научиться использовать команды для вывода информации о текущем состаянии пулов.

  - Получить навыки работы с созданием томов и установкой параметров.
  
  -  Научиться создавать снапшоты и восстанавливать состояние файловых систем из снапшотов на других хостах.
  - Выбирать подходящее сжатие для файловой системы.
  - С помощью команд zfs определять размер хранилища, тип пула, размер блока, какое сжатие и какая контрольная сумма используется. 

  
## Назначение vagrantfile

-  Создается две ВМ. Server - с системным диском на 10Гб + шесть дополнительных дисков по 1 Гб для дальнейшего создания на них пулов  zfs и Client - с одним системным диском на 10 Гб.
-  С помощью shell-скриптов выполняется:

    + Установка пакета zfs в ВМ и активация модуля ядра.
    + Активация фунции аутентификации по паролю для ssh.
    
   
## Примечание

> В репозитории приложен файл task_on_zfs.txt, с описанием выполнения домашнего задания.