<h2 class="c-project-heading--task">Use an apostrophe</h2>
--- task ---
Add a sentence that contains an apostrophe inside speech by using an escape character.
--- /task ---

<h2 class="c-project-heading--explainer">Don’t panic about apostrophes</h2>

If you want to use an apostrophe **inside** speech (like *That's mine!*), you can escape it using a backslash `\`.

This tells Python to treat the apostrophe as part of the sentence, not the end of the string.

<div class="c-project-code">
--- code ---
---
language: python
filename: picnic.py
line_numbers: true
line_number_start: 5
line_highlights: 6
---
print('It was a sunny day at the park. 🌳')
print('Three kids were sitting on a big picnic blanket, eating jam sandwiches. 🧺🥪')
print('A squirrel appeared and shouted, "Give that back!" 🐿️')
print('All three kids gasped loudly. 😲')
print("One kid's sandwich had already disappeared.")
print('Another kid yelled, "That\'s mine!"')
--- /code ---
</div>

<div class="c-project-output">
One kid's sandwich had already disappeared.<br />
Another kid yelled, "That's mine!"
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

Use `\'` inside a string to include an apostrophe without ending it too early.  
For example: `'That\'s funny!'`

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

If you get a *SyntaxError*, check that:<br />
- You used the backslash correctly before the apostrophe<br />
- You haven’t accidentally ended your string too early

</div>
