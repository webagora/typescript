---
id: 5900f5451000cf542c510057
title: 'Проблема 472: Комфортна відстань II'
challengeType: 5
forumTopicId: 302149
dashedName: problem-472-comfortable-distance-ii
---

# --description--

Є $N$ місць поспіль. $N$ людей приходять один за одним та займають місця згідно з даними правилами:

1. Жодна людина не сидить поруч з іншою.
1. Перша людина обирає будь-яке місце.
1. Кожна наступна людина вибирає місце, найбільш віддалене від того, хто вже сидить, до тих пір, поки воно не порушує правило 1. Якщо існує більше одного варіанту, що задовільняє цю умову, то людина обирає місце зліва.

Зверніть увагу, що через правило 1, деякі місця, безумовно, будуть вільними, і максимальна кількість осіб, які можуть бути розміщені, менша за $N$ (для $N > 1$).

Ось можливі розстановки для $N = 15$:

<img class="img-responsive center-block" alt="розстановка для N = 15" src="https://cdn.freecodecamp.org/curriculum/project-euler/comfortable-distance-ii.png" style="background-color: white; padding: 10px;" />

Ми бачимо, що якщо перша людина обирає правильно, то на 15 місцях може бути до 7 осіб. Ми також можемо бачити, що перша людина має 9 варіантів, щоб максимізувати кількість осіб, яких можна розмістити.

Нехай $f(N)$ буде кількістю варіантів, які перша людина має, аби максимізувати кількість людей для $N$ місць поспіль. Таким чином, $f(1) = 1$, $f(15) = 9$, $f(20) = 6$, та $f(500) = 16$.

Також $\sum f(N) = 83$ за $1 ≤ N ≤ N ≤ 20$ і $\sum f(N) = 13\\,343$ за $1 ≤ N ≤ 500$.

Знайдіть $\sum f(N)$ для $1 ≤ N ≤ {10}^{12}$. Впишіть останні 8 цифр вашої відповіді.

# --hints--

`comfortableDistanceTwo()` повинен повертатися як `73811586`.

```js
assert.strictEqual(comfortableDistanceTwo(), 73811586);
```

# --seed--

## --seed-contents--

```js
function comfortableDistanceTwo() {

  return true;
}

comfortableDistanceTwo();
```

# --solutions--

```js
// solution required
```
