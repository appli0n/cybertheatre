# cybertheatre
## What? 
### Что это?
This is a small special library to creating scenarios for music robot in Creative laboratory of robotics in ITMO. 

Это узкоспециализированная библиотека для конвертирования миди-файлов в сценарии для роботов-музыкантов из Творческой лаборатории робототехники в ИТМО

You can read about us where:

Вы можете узнать о нас здесь:

* https://start.itmo.ru/tlabrobot/robot
* https://vk.com/tlabrobot
* https://www.youtube.com/@creativeroboticslab9567

## For who?
### Для кого?
It's only for people, who works with scenarios in our TLab. It's fully useless to other people.

Эта библиотека создана только для людей, которые работают со сценариями в нашей Лабе. Для остальных она, скорее всего, бесполезна.

## Functions
    number_from_note(i)

return name of note from its number in MIDI-file (int)

    note_from_number(i)

return number of note in MIDI-file from its name (str)

    elsa_note(i)

return format of note's name for scenario to robot Elsa
    
    elsa_file(in_filename, out_filename='melody', tempo=0, transposition=0, finger_delay=0)

write scenario to robot Elsa to file '{out_filename}_elsa.txt ' 