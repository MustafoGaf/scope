# Мавзуъхои асосии ин статя

1. scope
2. Hoisting
3. Recursion
4. Closur



1. SCOPE -область видимость <br/>
В JS область деляться на 4 тыпа 
а) Global scope - глобальные область выдимость которые объявляется на верху файла
И доступ на его возможно для всех осталные область 
<br/>
**Пример**<br/>
![alt](/путь/к/изображению.jpg)
<br/>
b)function scope - область функция Это единствение область которые делает глобалные (var) локальный
<br/>

**Пример**<br/>
function Sum(){<br/>
**//Это область функции**<br/>
}<br/>
c) Block scope - это область for и if <br/>
В этом област если мы объявляем перемение с помощю const и let, перемение будеть локалные 
. А если объявлем с var  то будеть глобалный и работаеть за придел данного областа
<br/>
**Пример** <br/>
d) Module scope - делаеть глобалные перемени файла уникалные.
<br/>

# 2.Hoisting- поднятые <br/>
Это когда мы вызываем перемение или функция перед объявление
1)function Decloration - когда мы объявляем function decloration перед объявление это функция работает
<br/>
**Пример**<br/>
<br/>

2)let, const - будеть ошибка RefereshEror и TDZ (Temporal Dead Zone) то есть не рабоьаеть на практика

**Пример**<br/>
<br/>
3) var - Работаеть но не можеть получить значение перемении (будеть undefined) <br/>
**Пример**<br/>

# 3. Recursion - это функция которые возвращает само себя. Это функция алтернатив цикла
*Это фунция должно имет условые если мы не исползуем условые то функция работат будеть бесконечно*
**Пример**<br/>

# 4. Closur




