---
id: 587d7b83367417b2b2512b33
title: Використання консолі JavaScript для перевірки значення змінної
challengeType: 1
forumTopicId: 18372
dashedName: use-the-javascript-console-to-check-the-value-of-a-variable
---

# --description--

І Chrome, і Firefox мають чудові консолі, також відомі як DevTools, для налагодження роботи вашої JavaScript.

Ви можете знайти інструменти розробника в меню вашого Chrome або у веб-консолі в меню Firefox. Якщо ви використовуєте інший браузер або мобільний телефон, ми наполегливо радимо вам натомість працювати з комп'ютерною версією Firefox або Chrome.

Метод `console.log()`, який "виводить" вихідні дані з тих, що знаходяться між його дужками до консолі, імовірно, буде найкориснішим інструментом для налагодження програм. Розміщення його у стратегічно важливих місцях вашого коду може показати вам проміжні значення змінних. Добре мати уявлення про те, яким повинен бути результат, перш ніж розглянути, яким він є. Формування ключових моментів для розуміння стану ваших розрахунків у всьому коді допоможе скоротити кількість місць для пошуку проблеми.

Ось приклад виведення на екран консолі рядка `Hello world!`:

```js
console.log('Hello world!');
```

# --instructions--

Використайте метод `console.log()`, щоб вивести на екран значення змінної `a`, де це вказано в коді.

# --hints--

Ваш код повинен використовувати `console.log()` для перевірки значення змінної `a`.

```js
assert(code.match(/console\.log\(a\)/g));
```

# --seed--

## --seed-contents--

```js
let a = 5;
let b = 1;
a++;
// Only change code below this line


let sumAB = a + b;
console.log(sumAB);
```

# --solutions--

```js
var a = 5; console.log(a);
```
