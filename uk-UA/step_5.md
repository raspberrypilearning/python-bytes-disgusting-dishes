<h2 class="c-project-heading--task">Заверши рецепт і додай попередження</h2>

\--- task ---

Надрукуй останні кроки рецепта й завершальне попередження, використовуючи подвійні лапки.

\--- /task ---

<h2 class="c-project-heading--explainer">Підготуйся</h2>

Рецепт майже готовий! Тепер додай останні кроки, щоб шеф-кухар знав, як завершити приготування страви.

Не забудь додати попередження в кінці — цю огидну страву слід їсти тільки зомбі!  
У цьому повідомленні слово <code>З'їсти</code> містить апостроф, тому рядок потрібно взяти в подвійні лапки <code>" "</code>.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 13
line_highlights: 13-16
---

print('3. Додай очні яблука і перемішуй, доки вони не почнуть витріщатися на тебе у відповідь.')
print('4. Полий зверху слизом і подавай холодним. ❄️')
print()
print("💀 УВАГА: З'їсти це можуть тільки зомбі!")

\--- /code ---

</div>

<div class="c-project-output">
<pre>🤢 Ласкаво просимо до кулінарної книги «ОГИДНІ СТРАВИ»! 🤮

🧠 Інгредієнти:

- 1 склянка обрізків нігтів на ногах 🦶
- 2 протухлі яйця 🥚
- Жменя ворсу з пупка 🤏
- 3 очні яблука 👁️👁️👁️
- Зелений слиз на свій смак 🧪

🧪 Вказівки:

1. Змішай обрізки нігтів із яйцями у брудній шкарпетці.
2. Посип ворсом з пупка.
3. Додай очні яблука і перемішуй, доки вони не почнуть витріщатися на тебе у відповідь.
4. Полий зверху слизом і подавай холодним. ❄️

"💀 УВАГА: З'їсти це можуть тільки зомбі!"</pre>

</div>

<div class="c-project-callout c-project-callout--tip">

### Порада

Для більшості рядків можна використовувати одинарні лапки <code>' '</code>. Але якщо текст містить апостроф, наприклад у слові <code>З'їсти</code>, використовуй подвійні лапки <code>" "</code>.

</div>

<div class="c-project-callout c-project-callout--debug">

### Налагодження

- Переконайся, що попередження взято в подвійні лапки.<br />
- Не забувай друкувати кожен крок з нового рядка.<br />
- Додавай кожне повідомлення через <code>print()</code>

</div>

<div class="c-project-callout c-project-callout--tip">

### Зворотний зв’язок

Це бета-проєкт, тобто він абсолютно новий і доступний не скрізь. Якщо ви тестували цей проєкт самостійно або зі своїм клубом, поділіться своєю думкою.

<a href="https://form.raspberrypi.org/4874054?tfa_6933=python-bytes-disgusting-dishes" style="
display: inline-block;
padding: 10px 20px;
border: 2px solid black;
border-radius: 999px;
font-weight: bold;
font-size: 16px;
background-color: white;
color: black;
text-align: center;
text-decoration: none;
transition: background-color 0.2s;
" onmouseover="this.style.backgroundColor='#f0f0f0';" onmouseout="this.style.backgroundColor='white';">
Залишити відгук </a>

</div>
