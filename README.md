__JavaScript Style Guide__
### 1.Понятные имена переменных и функций
*Bсегда начинаются со строчной буквы, имена, состоящие из нескольких слов, записываются с использованием верблюжьего стиля (camelCase)*

😃 lastName, name1

😠 NameOfFunction, 123name, nomer
***
### 2.Комментирование
*Не нужно комментировать очевидные вещи, добавлять в код комментарии, которые не помогают разобраться в его сути.*
***
### 3.Фигурные скобки
*Открывающая фигурная скобка располагается на той же строке. Перед скобкой пробел. Закрывающая скобка располагается на новой строке.*

😃
       
    function edit(name, age) {
      if (age < 100) {
      }
    }
    
😠

    function edit(name, age)
    {
      if (age < 100) {/*тело цикла*/}
    }
***
# 4.Точки с запятыми обязательны!!!
😃 let hello = 'Hello';

😠 let hello = 'Hello'
***
### 5.Не используйте var
*Объявляйте все переменные с помощью const или let.*

😃 let hello = 'Hello';

😠 var hello = 'Hello';
***
### 6.Объявляйте переменные по одной
😃 

    let a = 1;
    let b = 2;
    let c = 3;

😠 

    let a = 1, b = 2, c = 3; 
***
## 7.Отступы
*Для отступов ключевых слов, операторов и т. д. используется не более одного пробела*

😃 
    
    const number = 1;

😠

    const number      =      2;
***
### 8.Длина строки
*Максимальная длина строки от 80 до 120 символов*
***
### 9.Уровень вложенности
*Уровней вложенности должно быть немного*

😃

    for (var i = 0; i < 10; i++) { if (i не подходит) continue; ... // <- уровень вложенности 1 }

😠

    for (var i = 0; i < 10; i++) {
      if (i подходит) {
      ... // <- уровень вложенности 2
      }
    }
***
### 10.Использовать квадратные скобки при создании массива
😃 let arr = []

😠 let arr = new Array();
