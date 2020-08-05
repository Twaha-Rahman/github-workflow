---
id: 5900f3ad1000cf542c50fec0
challengeType: 5
title: 'Problem 65: Convergents of e'
forumTopicId: 302177
localeTitle: 'Задача 65: Конвергенты e'
---

## Description
<section id='description'>
Квадратный корень из 2 можно записать в виде бесконечной цепной дроби. <p> √2 = 1 + 1 </p><p> 2 + 1 </p><p> 2 + 1 </p><p> 2 + 1 </p><p> 2 + ... </p><p> Бесконечную непрерывную дробь можно записать: √2 = [1; (2)], (2) указывает, что 2 повторяется до бесконечности. Аналогичным образом √23 = [4; (1,3,1,8)]. Оказывается, что последовательность парциальных значений цепных дробей для квадратных корней обеспечивает наилучшие рациональные аппроксимации. Рассмотрим сходимости для √2. </p><p> 1 + 1 = 3/2 </p><p> 2 </p><p> 1 + 1 = 7/5 </p><p> 2 + 1 </p><p> 2 </p><p> 1 + 1 = 17/12 </p><p> 2 + 1 </p><p> 2 + 1 </p><p> 2 </p><p> 1 + 1 = 41/29 </p><p> 2 + 1 </p><p> 2 + 1 </p><p> 2 + 1 </p><p> 2 </p><p> Следовательно, последовательность первых десяти сходящихся для √2 равна: 1, 3/2, 7/5, 17/12, 41/29, 99/70, 239/169, 577/408, 1393/985, 3363/2378 , ... Самое удивительное, что важная математическая константа e = [2; 1,2,1, 1,4,1, 1,6,1, ..., 1,2k, 1, ...]. Первые десять членов в последовательности сходящихся для e: 2, 3, 8/3, 11/4, 19/7, 87/32, 106/39, 193/71, 1264/465, 1457/536,. .. Сумма цифр в числителе 10-го сходящегося числа равна 1 + 4 + 5 + 7 = 17. Найдите сумму цифр в числителе 100-го сходящегося непрерывной дроби для e. </p>
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler65()</code> should return 272.
    testString: assert.strictEqual(euler65(), 272);

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler65() {
  // Good luck!
  return true;
}

euler65();

```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```

</section>