# Hangman game
###### Made on [the course from Stepik](https://stepik.org/course/58852/info)

### Описание проекта "Угадайка слов (Виселица)": 

Программа реализует известную словесную [игру "Виселица"](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)).

Программа загадывает слово (из 1000 возможных), а пользователь должен его угадать.  

Изначально все буквы слова неизвестны. Также рисуется виселица с петлей. Пользователь предлагает букву, которая может входить в это слово.  
Если такая буква есть в слове, то программа ставит букву столько раз, сколько она встречается в слове.  
Если такой буквы нет, к виселице добавляется круг в петле, изображающий голову. Пользователь продолжает отгадывать буквы до тех пор, пока не отгадает всё слово.  
За каждую неудачную попытку добавляется еще одна часть туловища висельника (всего чно их 6: голова, туловище, 2 руки и 2 ноги).