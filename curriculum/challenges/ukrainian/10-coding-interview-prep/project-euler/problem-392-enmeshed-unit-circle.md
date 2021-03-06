---
id: 5900f4f41000cf542c510007
title: 'Задача 392: Взаємозалежне одиничне коло'
challengeType: 5
forumTopicId: 302057
dashedName: problem-392-enmeshed-unit-circle
---

# --description--

Прямолінійна сітка – це прямокутна сітка, де відстань між лініями не повинна бути рівновіддаленою.

Прикладом такої сітки є логарифмічний розграфлений листок.

Розглянемо прямолінійні сітки у декартовій системі координат з наступними властивостями:

- Сітки є паралельними до осей координатної системи Декарта.
- Є $N + 2$ вертикальні та $N + 2$ горизонтальні сітки. Отже, це $(N + 1) \times (N + 1)$ прямокутні клітинки.
- Рівняннями двох зовнішніх вертикальних сіток є $x = -1$ та $x = 1$.
- Рівняннями двох зовнішніх горизонтальних сіток є are $y = -1$ та $y = 1$.
- Клітинки сітки позначені червоним, якщо вони перекривають одиничне коло, чорним – якщо навпаки.

Для цього завдання вам варто знайти положення залишених $N$ внутрішніх горизонтальних та $N$ внутрішніх вертикальних сіток, аби площа, зайнята червоними клітинками, мінімалізувалася.

Наприкл. це малюнок вирішення для $N = 10$:

<img class="img-responsive center-block" alt="розв'язок для N = 10" src="https://cdn.freecodecamp.org/curriculum/project-euler/enmeshed-unit-circle.png" style="background-color: white; padding: 10px;" />

Площа, зайнята червоними клітинками, для $N = 10$, округлена до 10 знаків після коми, дорівнює 3.3469640797.

Знайдіть положення для $N = 400$. У своїй відповіді зазначте площу, зайняту червоними клітинками, округлену до 10 знаків після коми.

# --hints--

`enmeshedUnitCircle()` має вивести `3.1486734435`.

```js
assert.strictEqual(enmeshedUnitCircle(), 3.1486734435);
```

# --seed--

## --seed-contents--

```js
function enmeshedUnitCircle() {

  return true;
}

enmeshedUnitCircle();
```

# --solutions--

```js
// solution required
```
