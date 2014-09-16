# Резюме

`$ npm install -g coffee-script` - установка CoffeScript (после установки [Node.js](http://nodejs.org/) и [npm](http://npmjs.org/))    
<table>
    <tr>
        <th>CoffeeScript</th>
        <th>JavaScript</th>
    </tr>
    <tr>
        <td>== is</td>
        <td>===</td>
    </tr>
    <tr>
        <td>!= isnt</td>
        <td>!==</td>
    </tr>
    <tr>
        <td>not</td>
        <td>!</td>
    </tr>
    <tr>
        <td>unless что-то
            (пока не)
        </td>
        <td>!что-то</td>
    </tr>
    <tr>
        <td>and</td>
        <td>&&</td>
    </tr>
    <tr>
        <td>or</td>
        <td>||</td>
    </tr>
    <tr>
        <td>true yes on</td>
        <td>true</td>
    </tr>
    <tr>
        <td>false no off</td>
        <td>false</td>
    </tr>
    <tr>
        <td>@</td>
        <td>this</td>
    </tr>
    <tr>
        <td>a < b < c</td>
        <td>a < b && b < c</td>
    </tr>
    <tr>
        <td>a?</td>
        <td>typeof a !== "undefined" && a !== null</td>
    </tr>
    <tr>
        <td>"строка #{переменная}"</td>
        <td>"строка" + переменная</td>
    </tr>
    <tr>
        <td>if/then/else</td>
        <td>?/:</td>
    </tr>
    <tr>
        <td>switch/when/else</td>
        <td>switch/case/default</td>
    </tr>
    <tr>
        <td>что-то if условие     
            ИЛИ       
            if условие что-то
        </td>
        <td>if (условие) {что-то};</td>
    </tr>
    <tr>
        <td>имяПеременной = 'что-то'</td>
        <td>var имяПеременной = 'что-то';</td>
    </tr>
    <tr>
        <td>range = [1..10]     
            ИЛИ     
            range = [1...11]
        </td>
        <td>var range = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];</td>
    </tr>
    <tr>
        <td>имяОбъекта = свойство: 'значение', метод: -> 'что-то'     
            ИЛИ     
            имяОбъекта =    
            	свойство: 'значение'
            	метод: -> 'что-то'
        </td>
        <td>var имяОбъекта = {    
            	свойство: 'значение',    
            	метод: function () {    
            		return 'что-то';    
            	}    
            };
        </td>
    </tr>
    <tr>
        <td>for элемента in коллекции     
            	сделать что-то if условие     
            ИЛИ     
            сделать что-то for элемента in колекции when условие
        </td>
        <td>for (элемента in коллекции)     
            	if (условие) {    
            		сделать что-то;    
            	}
        </td>
    </tr>
    <tr>
        <td>имяФункции = -> 'что-то'</td>
        <td>var имяФункции = function () {    
            	return 'что-то';    
            };
        </td>
    </tr>
    <tr>
        <td>имяФункции = (аргумент1, аргументN) -> 'что-то'</td>
        <td>var имяФункции = function (аргумент1, аргументN) {    
            	return 'что-то';    
            };
        </td>
    </tr>
    <tr>
        <td>имяФункции = (аргумент = 'что-то') -> аргумент    
            (присвоение значения аргументу по умолчанию)
        </td>
        <td>var имяФункции = function (аргумент) {     
            	if (аргумент == null) {    
            		аргумент = 'что-то';    
            	}    
            	return аргумент;    
            };
        </td>
    </tr>
</table>