# Резюме

`$ npm install -g coffee-script` - установка CoffeScript (после установки [Node.js](http://nodejs.org/) и [npm](http://npmjs.org/))    
| CoffeeScript | JavaScript |
| —————— | —————|        
| == is | === |
| != isnt | !== |
| not | ! |
| unless что-то   
  (пока не) | !что-то |
| and | && |
| or | || |
| true yes on | true |
| false no off | false |
| @ | this |
| a < b < c | a < b && b < c |
| ```coffeescript
            a?
            ``` | ```javascript
            typeof a !== "undefined" && a !== null
            ``` |
| "строка #{переменная}" | "строка" + переменная |
| if/then/else | ?/: |
| switch/when/else | switch/case/default |
| ```coffeescript
            что-то if условие
            ```
            ИЛИ
            ```coffeescript
            if условие что-то
            ``` | ```javascript
            if (условие) {что-то};
            ``` |
| ```coffeescript
            имяПеременной = 'что-то'
            ``` | ```javascript
            var имяПеременной = 'что-то';
            ``` |
| ```coffeescript
            range = [1..10]
            ```
            ИЛИ
            ```coffeescript
            range = [1...11]
            ``` | ```javascript
            var range = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
            ``` |
 | ```coffeescript
            имяОбъекта = свойство: 'значение', метод: -> 'что-то'
            ```
            ИЛИ
            ```coffeescript
            имяОбъекта =
                свойство: 'значение'
                метод: -> 'что-то'
            ``` | ```javascript
            var имяОбъекта = {
                свойство: 'значение',
                метод: function () {
                    return 'что-то';
                }
            };
            ``` | 
| ```coffeescript
            for элемента in коллекции
                сделать что-то if условие
            ```
            ИЛИ
            ```coffeescript
            сделать что-то for элемента in колекции when условие | ```javascript
            for (элемента in коллекции)
                if (условие) {
                    сделать что-то;
                }
            ``` | 
| ```coffeescript
            имяФункции = -> 'что-то'
            ``` | ```javascript
            var имяФункции = function () {
            return 'что-то';
            };
            ``` |
| ```coffeescript
            имяФункции = (аргумент1, аргументN) -> 'что-то'
            ``` | ```javascript
            var имяФункции = function (аргумент1, аргументN) {
                return 'что-то';
            };
            ``` |
| ```coffeescript
            имяФункции = (аргумент = 'что-то') -> аргумент
            ```
            (присвоение значения аргументу по умолчанию) | ```javascript
            var имяФункции = function (аргумент) {
                if (аргумент == null) {
                    аргумент = 'что-то';
                }
                return аргумент;
            };
            ``` |