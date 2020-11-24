# Provectus Internship Program test assignment

## Instructions

* Each test block consists of questions, and a code exercise
* You need to answer questions and complete the code exercise
    * Code exercise result must be on Stackblitz or Github
    * Answers can be in Russian or English language
* The result of the entire assignment must be on Google Docs or Github

## Assignment
#### Block 1: Common
    1. What are primitives? How can developers use them?
    Значения примтивного типа, такие как string, number, boolean, null, undefined, symbol и bigint.
    Примитивы не могут быть модифицированы. 
    В JS существуют объекты-обертки: String, Number, Boolean и Symbol. Они позволяют использовать методы объеков на примитивах.
    
    2. What does keyword `this` mean?
    В глобальном контексте this ссылается на глобальный объект
    Когда функция вызывается как метод объекта, используемое в этой функции ключевое слово this принимает значение объекта, по отношению к которому вызван метод.
    Когда функция используется как обработчик событий, this присваивается элементу с которого начинается событие.

    3. What are callbacks?
    callback - функция обратного вызова, которая передается в качестве аргумента в другую функцию и выполняется после того, как другая функция завершила выполнение.
    
    4. What is a function declaration and how are its types different?
   ```JS
   // Объявление функции (Function Declaration)
   function sayHi() {
     alert( " Hi" );
   }
   ```
   ```JS
   // Функциональное Выражение (Function Expression)
   let sayHi = function() {
     alert( "Hi" );
    };
   ```
    Function Declaration обрабатываются перед выполнением блока кода. Они видны во всём блоке.
    Функции, объявленные при помощи Function Expression, создаются, только когда поток выполнения достигает их.
    
    5. Compare spread and rest operators.
    Если "..." располагается в конце списка аргументов функции, то это «остаточные параметры». Он собирает остальные неуказанные аргументы и делает из них массив.
    Если "..." встретился в вызове функции или где-либо ещё, то это «оператор расширения». Он извлекает элементы из итерируемых объектов.

    
#### [Code exercise](https://stackblitz.com/edit/js-block1?file=task.js) - [solution (решение)](https://stackblitz.com/edit/js-block1-c33ito?file=task.js)

#### Block 2: Async
    1. JavaScript, is it synchronous or not?
    JS синхронный, может быть асинхронным с помощью колбеков, промисов и async/await

    2. What is the key principle of Call Stack?
    last in — first out, «последним пришёл — первым вышел»
    
    3. What does AJAX mean?
    Ajax означает Асинхронный JavaScript и XML.
    Технология которая позволяет осуществлять взаимодействие с сервером без необходимости перезагрузки страницы.
    
    4. Promise hell. How would you solve it?
    Все асинхронные действия должны возвращать промис
    
    5. How would you handle exceptions in JS? List two options.
    try..catch и throw
    
    6. Which framework would you choose for a new project? Explain why.
    React самый востребованый

#### [Code exercise](https://stackblitz.com/edit/js-llr1ac-async-task-xqvfc5) - [solution (решение)](https://stackblitz.com/edit/js-llr1ac-async-task-h8nkfo?file=index.js)


#### Block 3: TypeScript
    1. Is it possible to check types in runtime? If so, how?
    
    2. What is the difference between private and protected fields?
    Защищённые поля имеют префикс _. К таким полям необходимо обращаться только из его класса и классов, унаследованных от него, хоть к ним и есть доступ из вне
    Приватные поля имеют префикс #. Получить доступ к таким полям можно только внутри класса.

    3. How do interfaces help in development?
    
    4. How would you pass arguments into a Class?
    Для этого используется constructor(arguments)
#### [Code exercise](https://stackblitz.com/edit/typescript-2xfiqk) - [solution (решение)](https://stackblitz.com/edit/typescript-rdzyev)
