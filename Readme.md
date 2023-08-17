   What is a scope in js ? 
   Definition
A scope essentially defines which variables you can use/access. A scope is divided into a global, and local scopes.
A closure is an inner function, which has access to the parent/outer function scope.
Scopes
Variables exposed in the global scope, will be accessible from within the global scope, and all the other underlying local scopes. However, a variable inside a local scope, will not be directly accessible from another local scope or from the global scope. When you are declaring a variable outside a function, then you are declaring a global variab
 
 В js есть 4 вида скопа 
 -Global scope
 -Function scope
 -Block scope
 -Module scope

 Область относится к доступности переменных и функций в определенных частях кода.

В JavaScript переменная имеет два типа области:

Глобальный охват
Локальная область действия

FUnction scope - работает только в функции
block scope - if/for
module scope - для файлов

Hoisting (Подъем) — это механизм JavaScript, в котором переменные и функции
объявления перемещаются в верхнюю часть своей области перед кодом
исполнение
Temporal Dead Zone(TDZ) - Временная мертвая зона