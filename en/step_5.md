<h2 class="c-project-heading--task">Finish the recipe and add a warning</h2>
--- task ---
Print the last steps of your recipe and a final warning message using double quotes.
--- /task ---

<h2 class="c-project-heading--explainer">Set the scene</h2>

Your recipe is almost complete! Now add the final steps so the chef knows how to finish the dish.

Then add a warning message at the end — it's so disgusting that only zombies should eat it!  
This message uses an apostrophe in the word <code>Don't</code>, so you’ll need to use double quotes <code>" "</code> around the string.

<div class="c-project-code">
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 13
line_highlights: 13-16
---
print('3. Stir in the eyeballs until they stare back at you.')
print('4. Drizzle with slime and serve cold. ❄️')
print()
print("💀 WARNING: Don't eat this unless you're a zombie!")
--- /code ---
</div>

<div class="c-project-output">
🤢 Welcome to the DISGUSTING DISHES cookbook! 🤮<br />
<br />
🧠 Ingredients:<br />
 - 1 cup of toenail clippings 🦶<br />
 - 2 rotten eggs 🥚<br />
 - A handful of belly button fluff 🤏<br />
 - 3 eyeballs 👁️👁️👁️<br />
 - Green slime to taste 🧪<br />
<br />
🧪 Instructions:<br />
1. Mix the toenails and eggs in a dirty sock.<br />
2. Sprinkle in the belly button fluff.<br />
3. Stir in the eyeballs until they stare back at you.<br />
4. Drizzle with slime and serve cold. ❄️<br />
<br />
💀 WARNING: Don't eat this unless you're a zombie!
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

You can use single quotes <code>' '</code> for most strings, but if your text includes an apostrophe like <code>Don't</code>, you’ll need double quotes <code>" "</code> instead.

</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

- Did you use double quotes around the warning message?<br />
- Each step should still be printed on a new line<br />
- Use <code>print()</code> for every message

</div>
