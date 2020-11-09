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
    Объявление функции (Function Declaration)
    function sayHi() {
      alert( " Hi" );
    }

    Функциональное Выражение (Function Expression)
    let sayHi = function() {
      alert( "Hi" );
    };
    
    Function Declaration обрабатываются перед выполнением блока кода. Они видны во всём блоке.
    Функции, объявленные при помощи Function Expression, создаются, только когда поток выполнения достигает их.
    
    5. Compare spread and rest operators.
    Если "..." располагается в конце списка аргументов функции, то это «остаточные параметры». Он собирает остальные неуказанные аргументы и делает из них массив.
    Если "..." встретился в вызове функции или где-либо ещё, то это «оператор расширения». Он извлекает элементы из итерируемых объектов.

    
#### [Code exercise](https://stackblitz.com/edit/js-block1?file=task.js)

#### Block 2: Async
    1. JavaScript, is it synchronous or not?
    2. What is the key principle of Call Stack?
    3. What does AJAX mean?
    4. Promise hell. How would you solve it?
    5. How would you handle exceptions in JS? List two options.
    6. Which framework would you choose for a new project? Explain why.
#### [Code exercise](https://stackblitz.com/edit/js-llr1ac-async-task-xqvfc5)

#### Block 3: TypeScript
    1. Is it possible to check types in runtime? If so, how?
    2. What is the difference between private and protected fields?
    3. How do interfaces help in development?
    4. How would you pass arguments into a Class?
#### [Code exercise](https://stackblitz.com/edit/typescript-2xfiqk)

